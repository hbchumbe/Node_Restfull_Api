# Node_Restfull_Api
# 1.- This Api has to listen on a port and accepts incoming HTTP     request for post, get, put, delete and HEAD.
# 2.- The Api allows a client to connect, then create a new user , then edit and delete that user

# 3.- The APi ALlows a user to sign in  which gives them a token that they can use for a subsequent       authenticated request
# 4.- The  API allows  the user to sign  out which invalidates their token.
# 5.- The Api allows a signed in user to use their token to create  a new check.
# 6.- The APi allows a signed-in user to edit delete any of their checks
# 7.- in the background , workers perfom all the checks at the appropiete times, and send alerts to the users when check changes  its state from up to down or visa versa
# 8.- this does not men well be using a 3rd party library . quite the contrary
