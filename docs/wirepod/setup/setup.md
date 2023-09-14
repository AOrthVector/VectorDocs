## Before you begin setup

If using the T95, you will need an ethernet cable. You will plug one end of the cable into the T95 and the other end of the cable into an output port on the device that creates your wireless network. 

Verify that your PC is on the correct network. Vector can only communicate on the 2.4 GHz wireless network

On Windows, to check or change which wifi network your PC is on click on the wifi icon in the lower right of the screen

![Windows wifi indicator](/img/WifiIndicator.jpg)

Vector has to be on its charger for recovery mode and to pair with wire-pod via bluetooth

If you have multiple Vectors, you have to perform setup from the beginning for each Vector you own. 

## Prepare Vector for wire-pod

This will consist of the following steps

1. Put Vector in recovery mode so Vector's software can be updated
2. Pair Vector using bluetooth
3. Connect Vector to wifi
4. Vector receives new software

Vector's software needs to be updated to use wire-pod. You will put Vector in recovery mode to do this

!!! note   

    To see video of this next step [checkout the TechShop 82 video on YouTube](https://www.youtube.com/watch?v=hzlI7hPU-BM&t=358s) at 10:12

Press the button on top of Vector and do not release until you see blue lights start to move up Vector's head

Vector's screen will display either *anki.com/v*

Click on one of the links below to connect Vector to wire-pod

[https://keriganc.com/vector-wirepod-setup/html/main.html](https://keriganc.com/vector-wirepod-setup/html/main.html)

[https://vector.techshop82.com/html/main.html](https://vector.techshop82.com/html/main.html)

Next, Vector will pair with wire-pod via bluetooth

!!! tip   

    If you encounter any problems setting up Vector with wire-pod, there are multiple places to get help. See the Additional Resources and Troubleshooting links on this site for more information

    Also, even if yiou miss a step or make a mistake, you won't break Vector or your PC

### Bluetooth setup

To put Vector in bluetooth pairing mode give Vector two quick clicks on the top of his head

![Vector in pairing mode](/img/VectorReadyToPair.jpg)

In your web browser, click on the PAIR WITH VECTOR button and select your Vector

![Click on the button to pair Vector](/img/VectorPair.jpg)

Pairing can take multiple attempts. There's nothing wrong, it's just the nature of bluetooth. Click on Troubleshooting via the left side navigation for more information

After Vector displays the 6 digit pairing PIN, type the numbers into the box and click on the ENTER PIN button

After Vector is paired with wire-pod, you will connect Vector to your 2.4 GHz wireless network

### Connect Vector to wifi and update Vector

Select your 2.4 GHz network, enter the password for the network and click on CONNECT VECTOR TO WIFI

Vector's screen will start displaying an animated wifi logo

As soon the connection is successful, Vector's software update will begin. Vector's screen will display a cloud with rotating arrows and your web browser changes to indicate Vector is being updated

After Vector has received the new software, Vector will restart

When restart is complete, you will have to pair Vector via bluetooth again to move to the next step which is activating Vector with wire-pod

## Activate Vector with wire-pod

This is the step I had problems with. Some of the problems were mistakes I made:

* I had not switched my PC from a 5 GHz wireless network to the 2.4 GHz network
* I missed the step of putting Vector in recovery mode and updating Vector's software

The final issue was that Windows firewall was preventing activation. Fixing this required opening ports to allow traffic to flow through the Windows firewall

I had never done this before, but was able to work through it with the help of the [wire-pod installation](https://github.com/kercre123/wire-pod/wiki/Installation) page and online searches

To continue setup, click on Opening Ports in the left navigation menu