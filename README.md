# Pulse
An instant messenger compatible with ActivityPub
## Restrictions on Federation
* "Friend" in FediChat is treated as "follow" on ActivityPub.
* Reactions to messages from remote users of software for which reactions are not available are treated as "Like".
* FediChat cannot display public posts of remote users.
  * In the future, we plan to implement a "Feed" function that will allow users to view the public posts of the users they follow.
* Currently, FediChat users must be "Friends" (follow each other) in order to send messages from FediChat users but,  non-FediChat remote users are not affected by this restriction.
