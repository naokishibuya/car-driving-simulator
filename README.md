# Self-Driving Car Simulator 

This repo is originated from Udacity's Self-Driving Car Simulator (https://github.com/udacity/self-driving-car-sim).

## Installation

1. Before cloning this repository, install [Git LFS](https://git-lfs.github.com) to properly pull over large texture and model assets. 

Once, Git LFS is installed, run the following command once per your git account to enable it.

```
git lfs install
```

2. Clone this repository.

3. Install Unity (unity_2019.4.1f1)

https://unity3d.com/get-unity/download

Note: all the assets in this repository require Unity. 

4. Load Unity, Pick load exiting project and choice the `self-driving-car-sim` folder.

5. Build the simulator.

Go to **File** -> **Build Settings...**.

## Editing scenes 

1. Load up scenes by going to Project tab in the bottom left, and navigating to the folder Assets/1_SelfDrivingCar/Scenes. To load up one of the scenes, for example the Lake Track, double click the file LakeTrackTraining.unity. Once the scene is loaded up you can fly around it in the scene viewing window by holding mouse right click to turn, and mouse scroll to zoom.

2. Play a scene. Jump into game mode anytime by simply clicking the top play button arrow right above the viewing window.

3. View Scripts. Scripts are what make all the different mechanics of the simulator work and they are located in two different directories, the first is Assets/1_SelfDrivingCar/Scripts which mostly relate to the UI and socket connections. The second directory for scripts is Assets/Standard Assets/Vehicle/Car/Scripts and they control all the different interactions with the car.

4. Building a new track. You can easily build a new track by using the prebuilt road prefabs located in Assets/RoadKit/Prefabs click and drag the road prefab pieces onto the editor, you can snap road pieces together easily by using vertex snapping by holding down "v" and dragging a road piece close to another piece.

![Self-Driving Car Simulator](./sim_image.png)
