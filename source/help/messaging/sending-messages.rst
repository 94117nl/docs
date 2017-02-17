.. _sending-messages:

Messaging Basics
================

After a message has been sent, you or others can reply to it and link to it. Depending on which edition of Mattermost you have and how it's configured by the System Admin, you can also edit and delete your own messages.

Message Types
-------------

Mattermost has two types of messages: posts, and replies.

Posts
  Posts can be considered parent messages. They are the messages that often start a thread of replies. Posts can be written and sent from the text input box at the bottom of the center pane.

Replies
  Reply to posts to keep conversations organized in threads.

  Reply to a post by clicking the reply icon next to any message text. This action opens the right-hand sidebar (RHS) where you can see the message thread, then compose and send your reply. Replies are indented slightly in the center pane to indicate that they are child messages of a parent post.

  When composing a reply in the right-hand sidebar, click the expand/collapse icon with two arrows at the top of the sidebar to make things easier to read.

Sending a Message
-----------------

Write a message by typing into the text input box, then press **ENTER** to send it. Use **SHIFT+ENTER** to create a new line without sending a message. To send messages by pressing **CTRL+ENTER**, go to **Main Menu > Account Settings > Send messages on Ctrl + Enter**.

Editing a Message
-----------------

The ability to edit a message after it is sent depends on which edition you are using.

Team Edition
  You can always edit a sent message.

Enterprise Edition
  System Admins can turn editing off, or they can set a time limit. If a time limit is set, you can edit a message only if the time limit has not been reached. The default time limit is 300 seconds, but System Admins can change it.

Edit a message by clicking the **[...]** icon next to any message that you’ve sent, then click **Edit**. When you're done editing, press **ENTER** to save the changes. Message edits do not trigger new @mention notifications, desktop notifications, or notification sounds.

Deleting a message
------------------

The ability to delete a message after it is sent depends on which edition you are using.

Team Edition
  You can always delete a sent message, and Team Admins and System Admins can delete messages.

Enterprise Edition
  System Admins can restrict access to the delete feature, preventing you from deleting your messages. System Admins can also prevent your Team Admin from deleting messages.

Delete a message by clicking the **[...]** icon next to any message that you've sent, then click **Delete**. If you don't see the **Delete** option, then the delete feature was turned of by the System Admin.

Linking to a message
--------------------

The permalink feature creates a link to any message. Get the permalink to any message by clicking the **[...]** icon next to the a message, then click **Permalink > Copy Link**. Sharing this link lets other users view the linked message in the Message Archives. If the link is to a message in a Public Channel, any user of the team can see the message. If the link is to a message in a Private Group, only other users in the group can see the message.

.. tip::
  The timestamp that appears beside the username of any message is also a permalink.
