@-moz-document url-prefix("https://discordapp.com/channels/")
{
/* Make The Image Darker */
  .layer
  {
    background: none !important;
    /* background: rgba(0, 0, 0, 0.2) !important; */;
  }

/* Settings Image */
  .ui-standard-sidebar-view
  {
    background: url(http://i.imgur.com/LRa2DkW.png) !important;
    background-size: cover !important;
  }
/* Also Settings */
  .sidebar-region, .content-region
  {
    background: none !important;
  }

  .layers, .appMount-14L89u
  {
    background: none !important;
  }

/* Background Image URL Must be HTTPS */
  body
  {
    background: url(https://i.imgur.com/uTVZzkC.jpg) !important;
    background-size: cover !important;
    height: 100vh !important;
    background-repeat: no-repeat !important;
  }

  .guilds-wrapper
  {
    background: none !important;
  }

  .private-channels, .search-bar
  {
    background: none !important;
  }

  #friends, .friends-header, .friends-table
  {
    background: none !important;
  }

/* ===================================================== */
/* Scrollbar */
  .scroller::-webkit-scrollbar-thumb
  {
    border: none !important;
    background: linear-gradient(0deg, rgba(0, 0, 0, 0), rgb(91, 187, 255), rgba(0, 0, 0, 0)) !important;
  }
/* Also Scrollbar */
  .scroller::-webkit-scrollbar-track
  {
    background: linear-gradient(0deg, rgba(91, 187, 255, 0.4) 0%, rgba(0, 0, 0, 0) 5%, rgba(0, 0, 0, 0) 95%, rgba(91, 187, 255, 0.4) 100%) !important;
  }
/* Some Other Scrollbar Thingy */
  .scroller::-webkit-scrollbar
  {
    width: 7px !important;
  }
/* Another Scrollbar Thingy*/
  .scroller::-webkit-scrollbar-track-piece
  {
    border: none !important;
    background: none !important;
  }
/* ===================================================== */

/* Channels section */
  .channels-wrap, .flex-lFgbSz
  {
    background: none !important;
  }

/* Top Bar, Bottom Bar, Messages, Member List, Form, Channels */
  .content, .chat, .messages-wrapper, .scroller-fzNley, form, .channels-3g2vYe
  {
    background: none !important;
  }

/* Selected Text Chanel */
  .contentSelectedText-3j5CXt
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0), rgba(41, 137, 216, 0.4)) !important;
  }
/* Selected Text Chanel Hovered */
  .contentSelectedText-3j5CXt:hover
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.6), rgba(41, 137, 216, 0.4)) !important;
  }
/* Hovered Text Channel */
  .contentHoveredText-2HYGIY
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.6), rgba(0, 0, 0, 0)) !important;
  }

/* Unread Messages */
  .unread-23Kvxk
  {
    position: absolute;
    left: 10px;
    top: 30px;
    height: 1px;
    width: 90%;
    background: linear-gradient(90deg, rgba(0, 0, 0, 0), rgb(91, 187, 255), rgba(0, 0, 0, 0));
    opacity: 1 !important;
    animation: unread 3s ease-out infinite !important;
  }

  .guild.unread:before
  {
    background: rgba(91, 187, 255, 0.7) !important;
    animation: unread 3s ease-out infinite !important;
  }

/* Mentions Indicator */
  .wrapper-2xO9RX, .badge
  {
    background: rgb(41, 137, 216);
    animation: mentions 3s infinite !important;
  }

/* New Mentions Indicator */
  .new-messages-indicator
  {
    background: linear-gradient(90deg, black, rgb(91, 187, 255), black) !important;
  }

  .new-messages-bar
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.4), rgba(91, 187, 255, 0.4), rgba(0, 0, 0, 0.4)) !important;
  }

/* Text Input Enabled */
  .innerEnabled-gLHeOL
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.4), rgba(91, 187, 255, 0.4), rgba(0, 0, 0, 0.4)) !important;
  }
/* Text Input Disabled */
  .innerDisabled-1hSPu_
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.2), rgba(91, 187, 255, 0.2), rgba(0, 0, 0, 0.2)) !important;
  }

  .jump-to-present-bar
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.4), rgba(91, 187, 255, 0.4), rgba(0, 0, 0, 0.4)) !important;
  }

/* Newe Messages Divider */
  .divider.divider-red:before
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.4), rgba(91, 187, 255, 0.4), rgba(0, 0, 0, 0.4)) !important;
  }
/* Also Newe Messages Divider */
  .divider.divider-red > div
  {
    background: none !important;
  }
/* Some More Newe Messages Divider */
  .divider.divider-red > span
  {
    background: rgb(11, 107, 186) !important;
    color: rgb(91, 187, 255) !important;
    animation: mentions 3s infinite !important;
  }
/* Divider */
  .divider:before
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.4), rgba(91, 187, 255, 0.4), rgba(0, 0, 0, 0.4)) !important;
  }
/* Some More Divider */
  .divider > div
  {
    background: none !important;
  }
/* Even More Divider */
  .divider > span
  {
    background: rgb(68, 94, 115) !important;
    color: rgb(91, 187, 255) !important;
  }

/* Loading More Messages */
  .loading-more
  {
    border: none !important;
    background: none !important;
  }
/* Also Loading More Messages */
  .has-more > button
  {
    color: rgb(91, 187, 255) !important;
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.4), rgba(91, 187, 255, 0.4), rgba(0, 0, 0, 0.4)) !important;
  }

/* Mention */
  .mentioned > .body > .message-text
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.4) 0%, rgba(0, 0, 0, 0) 70%) !important;
  }
/* Also Mention */
  .mentioned > .body > .message-text:after
  {
    background: rgb(41, 137, 216) !important;
    border-color: rgb(41, 137, 216) !important;
  }

/* ``` Code Comment */
  .hljs
  {
    background: rgba(91, 187, 255, 0.2) !important;
    border: 1px solid rgba(91, 187, 255, 0.4) !important;
    border-radius: 5px !important;
  }
/* Idem */
  .markup > pre
  {
    background: none !important;
    border: none !important;
  }

/* DM Friends Menu */
  .btn-friends > a
  {
    background: none !important;
    border: 2px solid rgba(41, 137, 216, 0.3) !important;
  }
/* Same */
  .btn-friends.selected > a
  {
    background: none !important;
    border: 2px solid rgba(101, 197, 276, 0.5) !important;
  }

  .channel.private > a:hover
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.6), rgba(0, 0, 0, 0)) !important;
  }

  .friends-row:hover
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.6), rgba(0, 0, 0, 0)) !important;
  }

/* Friends Buttons Right */
  .friends-action
  {
    background-color: rgb(41, 137, 216) !important;
  }

/* Friends Top Bar Selected Item */
  .tab-bar-item.selected, .tab-bar-item-primary
  {
    background: rgb(41, 137, 216) !important;
  }

/* Private Chanel Selected Chat */
  .channel.selected.private > a
  {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0), rgba(41, 137, 216, 0.4)) !important;
  }
/* ^^ */
  .channel.selected.private > a:hover
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.6), rgba(41, 137, 216, 0.4)) !important;
  }

/* User Profile Popout Top */
  .headerNormal-1cioxU
  {
    background: rgb(41, 137, 216) !important;
  }
/* User Profile Popout Profile Border */
  .avatar-1BXaQj
  {
    border-color: rgb(101, 197, 255) !important;
  }
/* User Profile Popout Middle */
  .body-3rkFrF
  {
    background: rgb(60, 60, 60) !important;
    box-shadow: 0 -6px 6px rgba(0, 0, 0, 0.2) !important;
    border: none !important;
  }
/* User Profile Popout Down */
  .footer-2J5zqP
  {
    background: rgb(60, 60, 60) !important;
  }
/* User Profile Note */
  .note > textarea:focus
  {
    background: rgb(60, 60, 60) !important;
  }

/* Friends Icon */
  .friends-icon
  {
    background-color: rgb(1, 97, 176) !important;
  }
/* Same But Hover */
  .friends-icon:hover
  {
    background-color: rgb(41, 137, 216) !important;
  }

/* Modal Menu */
  .modal-3HOjGZ
  {
    background-color: rgb(41, 137, 216) !important;
  }

/* Some Popout Menu */
  .popout-menu
  {
    background-color: rgb(41, 137, 216) !important;
  }

  .popout-menu-item
  {
    color: white !important;
    transition: 0.4s !important;
  }

  .popout-menu-item:hover
  {
    background: rgba(0, 0, 0, 0.4) !important;
  }

  .popout-menu-item.invite
  {
    color: rgb(91, 187, 255) !important;
  }

  .popout-menu-item.leave
  {
    color: rgb(255, 97, 31) !important;
  }

  .popout-menu-icon
  {
    background-color: white !important;
    border-radius: 5px !important;
    border: 3px solid white !important;
  }

  .popout-menu-separator
  {
    display: none !important;
  }
/* Ends Here */

/* Member List Hover */
  .channel-members > .member:hover
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.6), rgba(0, 0, 0, 0)) !important;
  }

/* User Profile Modal */
/* ==================================================================================================== */
  #user-profile-modal > .scroller-wrap, #user-profile-modal > .empty
  {
    background: rgb(60, 60, 60) !important;
  }

  #user-profile-modal > .scroller-wrap > .guilds
  {
    background: none !important;
  }

  .tab-bar-container
  {
    background: rgb(41, 137, 216) !important;
    border-color: rgb(121, 217, 255) !important;
  }

  .tab-bar-item
  {
    color: rgb(121, 217, 255) !important;
  }

  .tab-bar-item.selected
  {
    color: white !important;
    border-color: white !important;
  }

  #user-profile-modal > .scroller-wrap > .guilds > .guild:hover
  {
    background: linear-gradient(90deg, rgba(91, 187, 255, 0.6), rgba(0, 0, 0, 0)) !important;
  }

  #user-profile-modal > .header
  {
    background: rgb(41, 137, 216) !important;
  }

  #user-profile-modal > .header:after
  {
    background: none !important;
  }

  #user-profile-modal > .avatar-wrapper
  {
    background-color: rgb(41, 137, 216) !important;
  }

  #user-profile-modal > .header > .header-info > .header-info-inner > .discord-tag, #user-profile-modal > .header > .header-info > .header-info-inner > .discord-tag > .discriminator, #user-profile-modal > .header > .header-info > .header-info-inner > .activity
  {
    color: white !important;
  }
/* ==================================================================================================== */

@  keyframes unread
  {
    0%{opacity: 0.3;
  }

  50%
  {
    opacity: 1;
  }

  100%
  {
    opacity: 0.3;
  }
}

@keyframes mentions
{
  0%
  {
    border: 1px solid rgba(41, 137, 216, 0);
  }

  10%
  {
    border: 1px solid rgb(41, 137, 216);
  }

  20%
  {
    border: 1px solid rgb(51, 147, 226);
  }

  30%
  {
    border: 1px solid rgb(81, 177, 255);
  }

  40%
  {
    border: 1px solid rgb(101, 197, 255);
  }

  50%
  {
    border: 1px solid rgba(101, 197, 255, 0);
  }

  100%
  {
    border: 1px solid rgba(41, 137, 216, 0);
  }
}
}
