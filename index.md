---
layout: default
---

![Representative Image](assets/images/RepFig.png)

<center>Localization using magnetic anomalies is a promising approach for GPS-denied navigation, particularly in challenging environments such as indoor spaces, heavily forested areas, and long-horizon mission scenarios. However, the high cost of precision magnetometers and the complexities of calibration, influenced by distortions from both the platform and the surrounding environment, present notable challenges like wider access for the broader community and the rapid advancement of research in the field. This paper explores a neural network-based sensor model designed to account for environmental factors as well as internal and external magnetic field influences. By addressing these factors, the proposed model provides a practical framework for simulating magnetic interference from both the environment and the vehicle itself. This paper presents a virtual experimental framework that is implemented using Nvidia Omniverse, offering a simulation environment where virtual and physical robots can obtain realistic sensor measurements. This testbed is expected to serve as a tool for investigating magnetic-based navigation algorithms without requiring extensive physical setups. This testbed is released publically for researchers to access and implement novel navigation and localization architectures.</center>

### Installation of Isaac Sim Environment

To install the Isaac Sim MagNav Sim, first download the zip file provided at the top of this page to create the environment. Extract these files to a folder you can easily locate: `/home/user/MagNavIsaacSim`

To run the robot sim environment, open NVIDIA's Omniverse launcher and run Isaac Sim with the ROS2 Bridge Extension

![Isaac Sim Launcher](assets/images/IsaacSimLauncher.png)

Then navigate to the folder you extracted the files to in either the content explorer, or from `File->Open`. You will see the two following assets in the extracted folder:

![Isaac Assets](assets/images/ContentTab.png)

Open the file called `MagNavVirtualTestbed.usd` which contains the environment used. You will see the environment which looks as follows:

![Isaac Testbed](assets/images/VirtualTestbedLayout.png)

You can now move onto the ROS2 package installation to control the robot in the virtual environment.

```bash
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
### Installation of Magnetometer Simulation

To run the simulated magnetometer please visit the [Github Repo](https://github.com/aprilab-uf/magnetometer-sim) for the magnetometer simulation provided.

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image


### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
