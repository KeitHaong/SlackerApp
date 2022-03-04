# Registration 
> When users register, they automatically login 
> A proper domain is used for the email used to register the account
> The token in the data will be under the key "token"
> For channel assuming that the user details for members is their u_id
> Flockr owner is the FIRST person registered, with u_id = 0.
> Flockr owner is able to access all channel functions despite not being in the channel. Basically admin powers. 

# Channel
> Users can only be invited into private channels, they cannot join themselves.
> Users can only join public channels themselves.
> Only the flockr owner or the owner of the channel can add a member of the channel as an owner.
> Only the flockr owner of the owner of the channel can remove a member as an owner of the channel.

# Channels
> The user that creates the channel is automatically the channel's owner.

# Message
> When a message is removed, only the actual message is deleted, details of the removed message such as message_id, u_id and time created still remain in the system.

# User
> Users are able to have the same first name and/or last name.
> Users aren't able to have the same email.
> Users aren't able to have the same display name (handle).
> Users can only update their name, email and handle if they already have a valid, authorised and registered user profile.
> Only the user can update their name, email and handle, the flockr owner or owner of the channel cannot do so.

# Other
> The user who created the channel is automatically given admin permissions.
> Users cannot search for messages in channels that they are not in.