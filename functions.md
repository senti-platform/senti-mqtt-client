# Senti-MQTT-Client functions

## Todo (tasks):
- WebHook on GitHub to publish "now"
- API for webhook
- On message = "reboot" on topic /sensor/update
- PM2 daemon 
- Make options argument work and require from external file
- Slack channel for subscribe/publish
- Push to Slack from client
- Get keepalive and topic info from API
- Get username + password from API (SSL)

## Done:
- On message = "now" on topic /sensor/update
- NodeJS execute bash command
- Remotely update the client from GitHub and restart

### PM2 Process Manager

PM2 Runtime is a Production Process Manager for Node.js applications with a built-in Load Balancer. It allows you to keep applications alive forever, to reload them without downtime and facilitate common Devops tasks.

```sh
npm install pm2 -g
```
