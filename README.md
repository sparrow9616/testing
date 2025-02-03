# Telegram File Sharing Bot

A Telegram bot to store and share files with features like forced subscription, auto-approval, multi-bot management, and premium plans.

## Features

- Store files in specified database channels
- Generate shareable links for files 
- Force subscribe to channels before accessing files
- Auto-approval system for join requests
- Multiple bot instances management
- Premium plans with timed access
- Payment gateway integration
- Welcome/Leave messages
- Access token system
- Database channel redundancy
- Shortlink support

## Commands

### User Commands
- `/start` - Start the bot and check access
- `/help` - Get help message with command list

### Admin Commands

#### Bot Management
- `/addbot [token]` - Add new bot instance
- `/removebot [token]` - Remove bot instance
- `/settings` - Configure bot settings
  - Auto Approval
  - Access Token
  - Auto Generate
  - Bot Management
  - Database Type
  - Multi-bot Settings

#### File Management
- `/batch` - Start batch file upload process
  - Send files to be included
  - Use `/makeit` to generate batch link
  - Use `/cancelbatch` to cancel process
- `/gen` - Generate links for files in database channel
- don't check ` /set_link` - Add file links to categories
  - INDIAN
  - GLOBAL  
  - DARK
  - RANDOM
  - Custom categories

#### User Management  
- `/free [user_id]` - Manage user privileges
  - Token Plans
  - Download Plans
  - Ban/Unban
- `/sudolist` - List all sudo users
- `/addsudo` - Add new sudo user
- `/delsudo` - Remove sudo user

### Premium Features

#### Token Plans
- Plan 1: 24 hour access
- Plan 2: 30 day access

#### Download Plans  
- Plan 1: 12 hour unlimited downloads
- Plan 2: 30 day unlimited downloads

## Environment Variables

Create a .env file based on sample.env and fill in the required values:

### Required Variables
```text
API_ID - Get from my.telegram.org
API_HASH - Get from my.telegram.org
BOT_TOKEN - Get from @BotFather
OWNER_ID - Your Telegram ID (multiple IDs separated by space)
DATABASE_URL - MongoDB connection string
DATABASE_NAME - MongoDB database name (default: Stranger)
```

### Channel IDs
```text
DATABASE_CHANNEL_1 - Main database channel ID
DATABASE_CHANNEL_2 - Backup database channel ID
WELCOME_CHAT - Welcome/Leave messages channel ID
```
### subscription channels
```textRFSUB - Request FSUB channels {channel_id: "name"}
FSUB - Force SUB channels {channel_id: "name"} 
PENDING_REQUEST - Pending request channels {channel_id: "name"}
```
### Premium Plans Configuration
```text
TOKEN_PLAN_1 - 24 hour access duration in seconds (default: 86400)
TOKEN_PLAN_2 - 30 day access duration in seconds (default: 2592000)
DOWNLOAD_PLAN_1 - 12 hour download duration in seconds (default: 43200)
DOWNLOAD_PLAN_2 - 30 day download duration in seconds (default: 2592000)

TOKEN_PLAN_1_PRICE - Plan 1 price in INR (default: 1)
TOKEN_PLAN_2_PRICE - Plan 2 price in INR (default: 1)
DOWNLOAD_PLAN_1_PRICE - Download plan 1 price in INR (default: 1)
DOWNLOAD_PLAN_2_PRICE - Download plan 2 price in INR (default: 1)
```
### Payment gateway
```text
CASHFREE_CLIENT_ID - Cashfree API client ID
CASHFREE_CLIENT_SECRET - Cashfree API client secret
```
### Optional Settings
```text
SHORTLINK_URL - URL shortener API URL (default: api.shareus.io)
SHORTLINK_API - URL shortener API key
VERIFY_EXPIRE - Token verification expiry in seconds (default: 86400)
IS_VERIFY - Enable/disable verification (default: True)
TUT_VID - Tutorial video URL
FORCE_MSG - Custom force subscribe message
CUSTOM_CAPTION - Custom file caption
PROTECT_CONTENT - Prevent forwarding files (default: True) 
AUTO_DELETE_CONTENT - Auto delete content after seconds (default: 600)
```
[![IMAGE ALT TEXT HERE](https://i.ytimg.com/vi/jADTdg-o8i0/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGBACGAY4AUAB&rs=AOn4CLBqrwmcUV3YnFK50ILfRje3rpIS1w)](https://www.youtube.com/watch?v=jADTdg-o8i0)
