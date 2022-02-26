Bug #1 found: In "auth.js" "/login" router does not await User.authenticate, resulting in a pending promise. Therefore not correctly authenticating the user
