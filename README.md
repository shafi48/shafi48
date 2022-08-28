docker run -d \
    -e BOT_TOKEN="123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11" \
    -e API_ID='12345' \
    -e API_HASH='0123456789abcdef0123456789abcdef' \
    -e CHANNELS='-10012345678' \
    -e ADMINS='123456789' \
    -e DATABASE_URI="mongodb+srv://...mongodb.net/Database?retryWrites=true&w=majority" \
    -e DATABASE_NAME=databasename \
    --restart on-failure \
    --name mediasearchbot botxtg/media-search-bot
