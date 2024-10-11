---
title: Code Page
tags:
  - B²
  - Deeper_Blue
  - Code
  - Incomplete
---
#### Repo Structure
---
[The repository](https://github.com/BengalBots-LSU/Deeper-Blue) is comprised of two main branches. The [`main`](https://github.com/BengalBots-LSU/Deeper-Blue) branch and the [`platform-io`](https://github.com/BengalBots-LSU/Deeper-Blue/tree/platform-io) branch.

In the `main` branch, a `.ino` file is simply hosted and there the file can easily be added to the Arduino IDE and uploaded to your board of choice.

In the `platform-io` branch, all the files required for a PlatformIO project are configured so you should be able to simply clone the repository and then upload to a board of your choice via PlatformIO.

#### Imports
---
This project required ==1== external library. \n
You'll want to download and import the [`Ps4 Controller Host Library`](https://github.com/pablomarquez76/PS4_Controller_Host) . You may be able to go ahead and simple do

```cpp
#include <PS4Controller.h>
```

