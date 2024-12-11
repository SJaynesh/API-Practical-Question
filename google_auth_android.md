<pre>
  
var googleSignOption = GoogleSignInOptions.Builder(GoogleSignInOptions.DEFAULT_SIGN_IN)
            .requestIdToken(getString(R.string.token_id)).requestEmail().build()

        var googleClient = GoogleSignIn.getClient(this@LoginActivity, googleSignOption)

        val registerGoogle =
            registerForActivityResult(ActivityResultContracts.StartActivityForResult()) {
                val googleId = GoogleSignIn.getSignedInAccountFromIntent(it.data)
                val credential = GoogleAuthProvider.getCredential(googleId.result.idToken, null)

                authHelper.auth.signInWithCredential(credential).addOnSuccessListener {
                    val intent = Intent(this,HomeActivity::class.java)
                    startActivity(intent)
                    finish()
                }
                    .addOnFailureListener {
                        Toast.makeText(this@LoginActivity, it.message, Toast.LENGTH_SHORT).show()
                    }
            }


        binding.googleBtn.setOnClickListener {
           var intent =  googleClient.signInIntent

            registerGoogle.launch(intent)
        }
</pre>
