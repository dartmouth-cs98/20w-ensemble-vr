# Ensemble
* Ensemble is a VR experience that places the user in a realistic concert environment with an audience and ensemble. The user practices a musical piece that includes accompaniment and the ensemble plays along with the user, adapting to his or her tempo and practice habits such as repeating passages.

## Architecture
* The frontend and all visual aspects are to be implemented using Unity3D and compatible C# scripts. Autodesk Maya will be used for modeling.
* The backend will be coded in Python in a separate companion app. This will allow the visual aspect of the project to run at full capacity without worry of computational exhaustion as a result of numerous probability calculations.
* The audio detection shall use the aubio Python library for its pitch and onset detection implementations.

## Setup
* Install Unity3D version 2019.2.19f1 if needed.
     * Import Oculus Integration from the asset store
     * Follow the doc (https://docs.google.com/document/d/1qQUxRkFI3ZYzungtmWm_m737iezlGOvsgwCqs6ibgjQ/edit) to ensure that settings are correct
* For the audio detection to run properly, execute the following commands:
`brew install portaudio`
`pip install pyaudio`
`pip install aubio`


## Deployment
* Clone this repository into any folder. Then, open the project in Unity! An Oculus Quest is required to run the application, so plug in an Oculus Quest into your computer via USB cable. Enable USB debugging on the Oculus Quest.
* Go to Build Settings, and ensure that it is building to Android. Go to player settings and ensure that Quest is set as the build target. Then, click Build and Run, save the .apk into any folder you would like, and enjoy!

## Authors
TODO: list of authors
* James Lee
* Bryan Shin
* Marshall Peng
* Soohwan Park
* Myles Holt
* Ryan Hyun

## Acknowledgments
