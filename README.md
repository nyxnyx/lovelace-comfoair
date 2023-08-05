# Homeassistant Lovelace  Comfoair card

![Image](https://raw.githubusercontent.com/TimWeyand/lovelace-comfoair/master/result.png)

# Installation

* Clone this repo into your `www` folder inside your configuration. So it will be: `config_folder/www/lovelace-mqttcomfoair`. 
* Edit your lovelace-ui.yaml or use the flat configuration mode in lovelace and add to the top:
```
resources:
  - type: module
    url: /local/lovelace-mqttcomfoair/comfoair-card.js
```

# Configuration

* Go to your Lovelace Dashboard
* Add a "MQTT Comfoair Card" via UI
* Check the Entity Selection

![Image](https://raw.githubusercontent.com/TimWeyand/lovelace-comfoair/master/comfoair_configuration.png)
![Image](https://raw.githubusercontent.com/TimWeyand/lovelace-comfoair/master/comfoair_configuration2.png)

# Controlling the Comfoair
* Click on the Fan Speed Icon

# ToDO
- [ ] Highlight the current Fan Speed Icon
- [ ] Control the Temperature
