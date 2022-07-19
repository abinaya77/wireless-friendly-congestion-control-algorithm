# abi-wireless-friendly-congestion-control-algorithm

Satosi Utsami , Salahuddin Muhammad Zalim Sabir (2013) proposed a algorithm which states that In recent years ,new delay-based congestion control mechanisms like  Caia-Hamilton Delay(CHD )or Caia Delay Gradient (CDG) are becoming popular due to their effectiveness even over wireless links. CHDand CDG  are designed to behave friendly with conventional TCP New Reno flows. However,due to their delay- based window update mechanisms, CHD or CDG performance is often vulnerable to the co-existing aggressive TCP New Reno flows. In addition, incase of CHD, it is practically very difficult to choose the optimum  values of tuning parameters with a view to ensuring the expected performance .In this paper, they  proposed a new mechanism to overcome the above issues .they named it as Wireless Friendly Congestion Control (WFCC ) . and their objective is to devise congestion control scheme that is (i)friendly with TCP New Reno flows over wireless links when deployed together, (ii)free from delicate operational parameters and (iii) robust against link errors under a wide range of network buffer space.they conduct a thorough evaluation of proposed approach by simulation as well as emulation. Their methodology is
Cwnd=cwnd/2  for Sdi  >dmin + ( dmax – dmin)VAR^packetloss 
Cwnd=no change for other conditions 
Where Sdi  >dmin + ( dmax – dmin)VAR^packetloss  , VAR=0.15 
 Results show that WFCC (i) can lead upto 250% improvement in performance compared toTCP New Reno schemes and (ii) are friendly with TCP New Reno flows over wireless links.The limitations is that it Concentrate only on the congestion avoidance window and  does not improve fairness. 
