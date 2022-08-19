# cmc-explorer

sudo crontab -e

*/3 * * * * cd /root/explorer && node scripts/sync.js update > /dev/null 2>&1

*/30 * * * * cd /root/explorer && node scripts/sync.js peers > /dev/null 2>&1
