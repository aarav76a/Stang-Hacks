cd ~/Downloads
rm -rf startup-upgraded
unzip startup-gen-upgraded.zip
cd startup-upgraded
echo "GROQ_API_KEY=key" > .env.local
echo "VERCEL_TOKEN=key" >> .env.local
echo "PEXELS_API_KEY=key" >> .env.local
npm install && npm run dev
