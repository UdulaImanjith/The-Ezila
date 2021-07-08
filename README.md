
{
      "name": "The Anki Vector",
      "description": "An Anime themed Telegram group management bot.",
      "logo": "https://telegra.ph/file/e10a45d0433a1ab6fed7b.jpg",
      "keywords": [
         "telegram",
         "anime",
         "group",
         "manager",
         "Ankivector"
      ],   
   "repository": "https://github.com/Damantha126/The-Anki-Vector",
   "addons": [
      {
         "options": {
            "version": "12"
         },
         "plan": "heroku-postgresql"
      }
   ],
   "buildpacks": [
    {
      "url": "https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest"
    },
    {
      "url": "heroku/python"
    }     
  ],      
   "env": {
      "TOKEN": {
         "description": "Your bot token. Get one from @BotFather duh",
         "required": true,
         "value": ""
      },
      "API_ID": {
         "description": "Get API_ID from my.telegram.org, used for telethon based modules.",
         "required": true,
         "value": ""
      },
      "API_HASH": {
         "description": "Get API_HASH from my.telegram.org, used for telethon based modules.",
         "required": true,
         "value": ""
      },    
      "SQLALCHEMY_DATABASE_URI": {
         "description": "Your postgres sql db, empty this field if you dont have one.",
         "required": false,
         "value": "sqldbtype://username:pw@hostname:port/db_name"
      },      
      "OWNER_ID": {
         "description": "Your user ID as an integer.",
         "required": true,
         "value": "1391755824"
      },
      "OWNER_USERNAME": {
         "description": "Your username without the @",
         "value": "Damantha_Jasinghe"
      },
      "SUPPORT_CHAT": {
         "description": "Your Telegram support group chat username where your users will go and bother you with shit But be like: MyGroupChatUsernameBlah. If this ever points to saitama support than consider you made an enemy.",
         "required": true,
         "value": "ankivectorUpdates"
      },
      "EVENT_LOGS": {
         "description": "Event logs channel to note down important bot level events, recommend to make this public. ex: '-123456'",
         "required": true,
         "value": "-123456798"
      },
      "JOIN_LOGGER": {
         "description": "A channel where bot will print who added it to what group, useful during debugging or spam handling.",
         "required": true,
         "value": "-123456798"
      },      
      "CASH_API_KEY": {
         "description": "Required for currency converter. Get yours from https://www.alphavantage.co/support/#api-key",
         "required": true,
         "value": "-xyz"
      },
      "TIME_API_KEY": {
         "description": "Required for timezone information. Get yours from https://timezonedb.com/api",
         "required": true,
         "value": "-xyz"
      },
      "DEV_USERS": {
         "description": "ID of users who are Devs of your bot (can use /py etc.). If you are a noob and would come and bother Saitama support then keep the current ID's here at they are and add yours.",
         "required": false,
         "value": "1391755824 1758509403 1848277863"
      },
      "sw_api": {
         "description": "Spamwatch API Token, Get one from @SpamWatchBot.",
         "required": false,
         "value": ""
      }, 
      "STRICT_GBAN": {
         "description": "Enforce gbans across new groups as well as old groups. When a gbanned user talks, he will be banned.",
         "value": "True"
      },
      "DRAGONS": {
         "description": "A space separated list of user IDs who you want to assign as sudo users.",
         "required": false,
         "value": "1391755824 1758509403 1848277863"
      },
      "DEMONS": {
         "description": "A space separated list of user IDs who you wanna assign as support users(gban perms only).",
         "required": false,
         "value": "1391755824 1758509403 1848277863"
      },
      "TIGERS": {
         "description": "A space separated list of user IDs who you wanna assign as tiger users.",
         "required": false,
         "value": "1391755824 1758509403 1848277863"
      },
      "WOLVES": {
         "description": "A space separated list of user IDs who you want to assign as whitelisted - can't be banned with your bot.",
         "required": false,
         "value": "1391755824 1758509403 1848277863"
      },
      "ENV": {
         "description": "Setting this to ANYTHING will enable environment variables. Leave it as it is",
         "value": "ANYTHING"
      },
      "WEBHOOK": {
         "description": "Setting this to ANYTHING will enable webhooks. If you dont know how this works leave it as it is",
         "required": false,
         "value": ""
      },
      "PORT": {
         "description": "Port to use for your webhooks. Better leave this as it is on heroku",
         "required": false,
         "value": ""
      },
      "URL": {
         "description": "The Heroku App URL",
         "required": false,
         "value": "https://<appname>.herokuapp.com/"
      },
      "No_LOAD": {
         "description": "Dont load these modules cause they shit, space separation",
         "required": false,
         "value": "cleaner rss connection"
      }, 
      "BL_CHATS": {
         "description": "List of chats you want blacklisted.",
         "required": false,
         "value": ""
      },
      "ALLOW_EXCL": {
         "description": "Set this to True if you want ! to be a command prefix along with /. Recommended is True",
         "value": "True"
      },
      "DONATION_LINK": {
         "description": "Optional: link where you would like to receive donations. If you are a noob, better leave it linking to paul",
         "required": false,
         "value": "https://www.paypal.me/PaulSonOfLars"
      },
      "DEL_CMDS": {
         "description": "Set this to True if you want to delete command messages from users who don't have the perms to run that command.",
         "value": "True"
      },
      "AI_API_KEY": {
      "description": "Make your bot talk using Intellivoid's chatbot API, get your key from https://coffeehouse.intellivoid.net/",
         "required": false,
         "value": ""
   },      
      "BAN_STICKER": {
         "description": "ID of the sticker you want to use when banning people.",
         "required": false,
         "value": ""
      },
      "WALL_API": {
         "description": "Required for wallpaper. Get your's from https://wall.alphacoders.com/",
         "required": false,
         "value": ""
      }
   },
   "keywords": [
      "telegram",
      "anime",
      "group",
      "manager",
      "daisy"
   ],
   "name": "Ankivector",
   "repository": "https://github.com/Damantha126/The-Anki-Vector"
}
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
