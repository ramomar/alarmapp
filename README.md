# Alarmapp

<p align="center">
   <a href="https://vimeo.com/287134023"><img width="420" src="https://user-images.githubusercontent.com/10622989/44749114-3ba28f80-aad7-11e8-910e-98da1302fe2c.png"></a>
</p>

Alarmapp is the result of an effort to revive an old alarm system using a [Particle Photon](https://www.particle.io/products/hardware/photon-wifi).

You can read a nice blog post [here](https://medium.com/@ramomar/reviviendo-un-sistema-de-ed577e232077) (spanish).

## Features

### Ionic control panel

- [Realtime system state updates (e.g., a window opens, a door closes, etc.)](https://github.com/ramomar/alarmapp-admin/issues/1#issuecomment-416682576).
- [Push notifications when system gets breached or is in panic mode](https://user-images.githubusercontent.com/10622989/44742820-718b4800-aac6-11e8-809b-cb4da787492f.png).
- Sentry for error reporting.
- Activate/deactivate system.
- Disable areas.
- Panic button.
- General summary view.
- Floor diagram summary view.
- Test siren button.
- [Pull down to refresh](https://user-images.githubusercontent.com/10622989/44743084-19a11100-aac7-11e8-9ffd-97dab33881b2.png).
- [_Push notifications not enabled_ alert](https://user-images.githubusercontent.com/10622989/44743034-f4ac9e00-aac6-11e8-8947-03b3a22967ae.png).
- [_Not watching anything_ alert (all areas are disabled or all areas are open)](https://github.com/ramomar/alarmapp-admin/issues/1#issuecomment-416690513).
- [_No network_ alert](https://github.com/ramomar/alarmapp-admin/issues/1#issuecomment-416687888).
- [_Trouble connecting_ alert](https://github.com/ramomar/alarmapp-admin/issues/1#issuecomment-416689480).

You can see more UI screenshots [here](https://github.com/ramomar/alarmapp-admin/issues/1).

### Platforms

- iOS.
- Android.
- Web.

## Project structure

The project is contained in many repos.

|Repository name | Description |
|----------------|-------------|
| [Alarmapp Admin](https://github.com/ramomar/alarmapp-admin) | A control panel for the system made with Ionic. |
| [Alarmapp PWA](https://github.com/ramomar/alarmapp-pwa) | A simpler and modern control panel for the system made with Flutter. |
| [Alarmapp Firmware](https://github.com/ramomar/alarmapp-firmware) | Firmware for the Particle Photon. |
| [Alarmapp Schematics](https://github.com/ramomar/alarmapp-schematics) | Schematic for interfacing the old alarm system with the Particle Photon. |
| [Alarmapp Functions](https://github.com/ramomar/alarmapp-functions) | Cloud functions for the system. E.g. Push Notifications. |


## Preview

### Admin preview
<p align="center">
  <img src="https://user-images.githubusercontent.com/10622989/44741599-2d4a7880-aac3-11e8-9959-4d49ef1ab0e5.gif"></a>
</p>

### Schematic preview
<p align="center">
  <img src="https://user-images.githubusercontent.com/10622989/44690106-54e80500-aa1f-11e8-8179-75d2a9ed222b.png"></a>
</p>
