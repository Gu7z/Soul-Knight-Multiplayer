# Soul-Knight-Multiplayer
This post was made to help other peoples who want to play soul knight online and doesnt know how to do that. Idk if it was posted before here. Let me know in the comments bellow... Oh, i'm not into a youtube video but i want to do someday.
Ok let's do it!

First of all you will need a pay card... to put $50 in my account xD.

Well, let's really goes into it.

The pay card is to create an amazon ec2 account.

Let'me explain what is amazon ec2.
Imagin that you will make a signature in an amazon service that will give you some "time" to let a computer turned on at they servers. You'll have one year to use this "computer" and after this you will pay for this, literally.

Requeriments to this:

 * Pay card to subscribe into amazon ec2 servers;
 * ssh knowlege (putty program in windows basically);
 * A friend to play with you (hardest part);
 * Open vpn installed in those two+ android devices;
 * The [android soul knight host apk](https://mshares.co/file/ndaGTD) installed by the people who'll host the game;

I'll not explain here how to make the step by step but i'll give links to make step-by-step

1. Create an account in [AWS](https://aws.amazon.com/);

2. [Make an openVPN for you](https://www.youtube.com/watch?v=1R7ZQzAKyNs); (i would recommend select the 10 connected devices at 0:30)
    1. Make a psswd easy for your and your friends.
    
3. Goes to the https://xx.xxx.xx.xx:943/admin/ page from your VPN;

4. login with your login "openvpn" and your passw from the step 2

5. Goes to configuration > vpn settings
    1. In "network address" put 10.8.0.0 and 24 in "# of Netmask bits"
    2. in Group Default IP Address Network put bellow the default "10.8.0.0/24"
    3. Specify the private subnets to which all clients should be given access do the same
    4. Should clients be allowed to access network services on the VPN gateway IP address? turn yes
    5. Save
    
6. Now in advanced VPN turn yes:
    1. Should clients be able to communicate with each other on the VPN IP Network
    2. Allow multiple concurrent VPN connections for a user
    3. save
    
7. Get the .ovpn file and send to your friends.

8. Now say "CONNECT IN OPENVPN PLEASE YOUR BEATYFULL LITTLE GUYS AND SEND ME THE IP AFTER CONNECT" to the peoples who will play with you.
    1. When they connect bellow the graph there is a "your private ip"
    2. Ask them for this ip if you are the hoster;
    
9. The hoster guy will need to put all this ips at the hoster app and so start
    1. The host cannot be in the multiplayer room before start, he will need to create the multiplayer room *after* the start in hoster app
    
10. Now your friends, will have to open the multiplayer in soul knight and connect
    1. Here you will "search for room" after the hoster create the multiplayer room, not the start button.
    
11. Play and be happy.

Hope i helped you guys. Any question please ask here.

SoRy fOur MA BaDENglISh xD
