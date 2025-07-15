#Shelly makes it feel like my home
Hello! The project I’m sharing with you is my home, a space where Shelly devices play a fundamental role in our daily comfort, efficiency, and sustainability.

This is not a house with fixed routines, because we don’t have them either. It’s a house that adapts to the weather, the seasons, our presence or absence, and even to our moments of rest. A home that responds with intelligence, but also with empathy.

## House energy efficiency and sustainability
At the heart of the system is the **Shelly Pro 3EM**, which monitors in real time what we consume, produce, and export. Thanks to it, we can make the most of our solar energy by adjusting consumption according to production. The **Shelly's 1PM, 2PM and Em** control specific "circuits" and appliances — like hubs, lights, outlets, or appliances — and automatically cut phantom loads when they aren't necessary. This combination allows us to match our consumption to our solar production and, on many days, live in off-grid mode with the house battery, with the house running solely on the energy we generate.

The same applies to energy surplus management: the pool cleaning system is triggered automatically with a **Shelly 1** whenever the **3EM** detects energy being exported to the grid. In winter, if we’re exporting more than 1 kWh and the temperature is below the target, electric radiators are activated in rooms with detected presence — typically the office.

On days when very high temperatures are forecast, the south-facing blinds close automatically **(Shelly 2PM)** if the outside temperature exceeds the indoor temperature **(Shelly BLU H&T)** and if the room is unoccupied — helping keep the house cool without using air conditioning.

The garden irrigation is also automated **(via Shelly 1)** and only runs if it hasn’t rained in the last three days and there’s no rain forecast for the day. The watering duration is based on the predicted temperature, adjusting to the actual needs of the plants while avoiding waste.

## Human-Centered Comfort
Lighting in hallways, bathrooms, garage, kitchen, and living areas turns on and off automatically based on motion **(Shelly BL Motion)** and presence sensors. In bedrooms and adjacent areas, the lighting adapts when someone is sleeping — creating a calm environment, respecting rest, and keeping automations active.

When leaving the house with the car, all I need to say is “Hey Google, open garage”, and both gates **(2x Shelly 1)** open automatically. If we leave through the main door and lock it, the system notifies us if any door, window, or gate was left open.

All of this silent intelligence is made possible by the reliability and versatility of Shelly devices. They measure, act, switch, and respond to context — allowing us to live with more comfort, safety, and efficiency, without giving up simplicity.

Like my boss says — it’s only 5% done. This smarthome, and especially the UX of the house, is constantly evolving, and Shelly is a big part of that. 
Looking forward to Gen 4!

The house has 5kWp solar panels and a 5kWh battery and use HomeAssistant to join all brands and technologies together.

1st floor
![smarthome 1st floor](https://github.com/Tjda/smarthome/blob/main/imgs/Floor%201.png)

2nd floor
![smarthome 2nd floor](https://github.com/Tjda/smarthome/blob/main/imgs/2nd%20floor.png)

Cave
![smarthome cave](https://github.com/Tjda/smarthome/blob/main/imgs/Cave.png)
