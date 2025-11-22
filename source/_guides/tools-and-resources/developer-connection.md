---
# Copyright 2025 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

title: Developer Connection
description: |
  How to enable and use the Pebble Developer Connection to install and debug
  apps directly from a computer.
guide_group: tools-and-resources
order: 3
---

In order to install apps from the local SDK using the `pebble` tool, the Pebble
Android or iOS app must be set up to allow a connection from the computer to the
watch. Two discrete actions are required: enabling developer mode for the
mobile application, and for the watch you wish to develop on. This enables
viewing logs and installing apps directly from the development environment,
speeding up development.

Follow the steps illustrated below to get started.


## Android Instructions

In the Pebble mobile app:

* Open the overflow menu by tapping the three dot icon at the top right and tap
  *Settings*.
  
  ![](/images/guides/publishing-tools/enable-dev-android-1.png =300x)
  
* Enable the *Developer Mode* option.
  
  ![](/images/guides/publishing-tools/enable-dev-android-2.png =300x)
  
* Tap *Developer Connection* and enable the developer connection using the
  toggle at the top right.
  
  ![](/images/guides/publishing-tools/enable-dev-android-4.png =300x)
  
* Make note of the 'Server IP' and use it with the `--phone` argument.


## iOS Instructions

These actions take place in the iOS mobile app.

### Enable Development on the mobile app

* Open the 'Settings' item in the tab bar.
  
  ![](/images/guides/publishing-tools/enable-dev-ios-1.png =300x)
  
* Enable the 'Use LAN developer connection' setting using the toggle.
  
  ![](/images/guides/publishing-tools/enable-dev-ios-2.png =300x)

### Enable Developemnt on a particular watch

* Open the 'Devices' item in the tab bar.

  ![](/images/guides/publishing-tools/enable-dev-ios-3.png =300x)

* Select your Pebble device of choice.

* Enable tbe 'Dev Connection' toggle.

* Take down your mobile device's IP address from Settings > Wi-Fi > _IPv4 Address_ > IP Address
  
* Make note of the 'Server IP' and use it with the `--phone <mobile_device_ip>` argument.
