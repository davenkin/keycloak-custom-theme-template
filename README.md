## How to use
- Start the app: `./start-docker-compose.sh`
- Open `http://localhost:8765`, login with `admin`/`admin`
- Enable `Terms and Conditions` required action in the realm level, see `Authentication` -> `Required Actions` -> `Terms and Conditions` -> `Enabled`
- Create a realm and a client, set the `Login theme` of the client to `custom-terms`
- Create a user, added `Terms and Conditions` required action to this user
- Login with this user, you will see the terms page
- Modify some theme files such as `terms.ftl`
- Refresh the terms page and you will see the changes immediately