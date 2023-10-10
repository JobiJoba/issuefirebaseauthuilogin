# Reproduction error flutter auth ui with non correct login information on email provider

To configure Firebase use the following command with a project named issueauthui 


flutterfire config \        
  --project=issueauthui \
  --ios-bundle-id=issue.firebaseauthui.issueauthlogin.dev


# Error received

[VERBOSE-2:dart_vm_initializer.cc(41)] Unhandled Exception: type 'int' is not a subtype of type 'String' in type cast
#0      FirebaseAuthHostApi.signInWithCredential
messages.pigeon.dart:1068
<asynchronous suspension>
#1      MethodChannelFirebaseAuth.signInWithCredential
method_channel_firebase_auth.dart:295
<asynchronous suspension>
#2      FirebaseAuth.signInWithCredential
firebase_auth.dart:517
<asynchronous suspension>
Lost connection to device.