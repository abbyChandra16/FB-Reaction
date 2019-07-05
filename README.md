# FB-Reaction
A library to integrate facebook reactions in simple view or in recyclerview easily.

Steps to integrate it into your project :
 Step 1. Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  
  
  Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.abbyChandra16:FB-Reaction:1.0'
	}
	
	
	
How to use :

Initialise it in your activity ->
 var reaction = Reaction()
 
 On a click listener call this method ->
 
  btnReaction.setOnClickListener {

            reaction.react(this, btnReaction)
        }
	
	
	It has two parameters context and  view.
