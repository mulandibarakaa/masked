    if ! yarn global add pm2; then
        echo -e "\e[31mFailed to install PM2.\e[0m"
        exit 1
    fi
else
    echo -e "\e[32mPM2 is already installed.\e[0m"
fi

# Clone the repository
echo -e "\e[33mCloning Levanter repository...\e[0m"
if ! git clone https://github.com/lyfe00011/levanter.git "$BOT_NAME"; then
    echo -e "\e[31mFailed to clone repository.\e[0m"
    exit 1
fi
cd "$BOT_NAME"

# Install dependencies
echo -e "\e[33mInstalling dependencies with Yarn...\e[0m"
if ! yarn install --network-concurrency 3; then
    echo -e "\e[31mFailed to install dependencies.\e[0m"
    exit 1
fi

# Create config.env file
echo -e "\e[33mCreating config.env file...\e[0m"
cat > config.env <<EOL
PREFIX=.
STICKER_PACKNAME=★ɱąʂƙɛɖ ცɛɬɬơཞ★𓃵™®°°°💉💚✨★𓆪
ALWAYS_ONLINE=false
RMBG_KEY=null
LANGUAGE=en
WARN_LIMIT=3
FORCE_LOGOUT=false
BRAINSHOP=159501,6pq8dPiYt7PdqHz3
MAX_UPLOAD=60
REJECT_CALL=false
SUDO=null,966541074275
TZ=Africa/Nairobi
VPS=true
AUTO_STATUS_VIEW=no-dl
SEND_READ=false
AJOIN=true
STATUS_VIEW_EMOJI = 🤍, 🌙, 🍥, 🦋, ☘️, ✨, 🍒, 🪻, 🌸, 🍃, 🧸
                      
EOL

echo "NAME=$BOT_NAME" >> config.env

if [ -n "$SESSION_ID" ]; then
    echo "SESSION_ID=$SESSION_ID" >> config.env
fi

# Start the bot
echo -e "\e[33mStarting the bot...\e[0m"
if ! pm2 start index.js --name "$BOT_NAME" --attach; then
    echo -e "\e[31mFailed to start the bot.\e[0m"
    exit 1
fi
