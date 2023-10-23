# Unity - Manual Activation

This is a repository of instructions on how to acquire the ALF and ULF files for activating Unity.


## Usage

### 1. Fork this repository

Fork this repository in order to work with GitHub Actions.


### 2. Open `Acquire activation file with GUI`

Open the `Acquire activation file with GUI` page.

For this repository, [here](https://github.com/mackysoft/Unity-ManualActivation/actions/workflows/ActivationWithGUI.yaml).

![OpenGitHubActionPage](https://user-images.githubusercontent.com/13536348/114270217-255a5f80-9a46-11eb-9555-febf8f20ae4e.jpg)


### 3. Run workflow

1. Click on the `Run workflow` drop-down
2. Specify the desired Unity version (e.g. 2019.4.0f1) from which you want to acquire the ALF file.
3. Click on the `Run workflow` button.

![RunWorkflow](https://user-images.githubusercontent.com/13536348/114270225-28555000-9a46-11eb-8589-9b225d819082.jpg)


### 4. Aquire ALF file

1. Acquire the `Unity_v20XX.X.XfX.alf` file from the artifacts on the completed workflow page.
2. Unzip the zip file you acquired.

![AcquireALF](https://user-images.githubusercontent.com/13536348/114270233-2db29a80-9a46-11eb-86d5-9d2ba52056d1.jpg)

### 5. Aquire ULF file

> Activation of the personal license is currently disabled in unity license page. Please refer to the following
> 
> https://github.com/game-ci/documentation/issues/408

1. Open the manual activation page of Unity. (https://license.unity3d.com/manual)
2. Activate using the `Unity_v20XX.X.XfX.alf` file you acquired.
3. Click `Download license file` to download the ULF file.

---

You can acquire the ULF file by following the above process.

If this does not work, please refer to the Game CI official documentation.

https://game.ci/docs/github/activation
