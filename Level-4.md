## level 4

**Render**
- *Frontend* - https://superdeployment-level-4-client-production.up.railway.app
- *Backend* - https://superdeployment-level-4-server-production.up.railway.app

**Railway**
- *Frontend* - https://superdeployment-level-4-client.onrender.com
- *Backend* - https://superdeployment-level-4-server.onrender.com

1. All Services Provide automatic CD
2. Had to add withCredentials: true in every axios request
3. Used CORS and other unused libraries like cookieparser, made app to use express.json() for json responses
4. Had to fix tailwindCSS config
5. Had to add packages named ajv and ajv-keywords to deploy website on render
