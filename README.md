# Radiokot's Umbrel apps

### Cloudflare Tunnel client
Access your Umbrel apps from the Internet using Cloudflare network.

<img src="https://raw.githubusercontent.com/Radiokot/umbrel-cloudflared/0f377f08ac8380ec5cd2e51702874841b465fefa/repository-assets/screen-1.png" width=400 />

## Get it on your Umbrel

App store URL:
```
https://github.com/Radiokot/umbrel-app-store.git
```

Follow one of the guides below to add this store:

<details>
  <summary>Video guide</summary>
  <br>  
  To add this store to your Umbrel, follow the steps shown in this demo using the store URL from above:
  
  
  https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4

</details>

<details>
  <summary>Umbrel CLI guide</summary>
  <br>
  You can use the Umbrel CLI as described below:

  To add an app store:
  ```bash
  sudo ~/umbrel/scripts/repo add https://github.com/Radiokot/umbrel-app-store.git
  
  sudo ~/umbrel/scripts/repo update
  ```
  
  To install an app from the app store
  ```bash
  sudo ~/umbrel/scripts/app install app-name
  ```
  
  To remove an app store:
  ```bash
  sudo ~/umbrel/scripts/repo remove https://github.com/Radiokot/umbrel-app-store.git
  ```
</details>

## Explore Umbrel community app stores
There are more app stores for your Umbrel maintained by community members. 

💎Check out the detailed list of stores in [smolgrrr's awesome-umbrel repo](https://github.com/smolgrrr/awesome-umbrel#community-appstores)
