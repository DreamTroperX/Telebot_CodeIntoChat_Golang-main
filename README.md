# Telebot_CodeIntoChat_Golang
The Telegram bot is written in Go and is designed to send a three-digit code to specific chats, pereventing errors in error.log file. 
The main functions of this code:
{ Initialising the logger and setting up a log file to save errors.
  Generating a random number within a specified range.
  Reading configuration parameters (bot token, message text, list of chat IDs) from the config.ini file using the viper library.
  Send messages to each chat from the list of IDs according to the configuration.  }
