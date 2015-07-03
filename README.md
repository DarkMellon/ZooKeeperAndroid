# ZooKeeperAndroid
ZooKeeperAndroid is a full android port of ZooKeeper 3.4.6. All source codes of ZooKeeper are retained except for some MBean(s) and  security function not available in Android environment.

As many people has mentioned before, ZooKeeper should normally be used in INERTNAL network environment rather than Internet. Also, facilities like Curator should be seriously taken into considerations to handle situation such as connection lose etc. It is reasonable that Apache says Guava is to Java what Curator is to ZooKeeper.

However, judging from what I have experienced since I used the Android port version of ZooKeeper, I really DO NOT think using ZooKeeper in Android environment is a good idea. 