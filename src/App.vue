<template>
  <div id="app">
    <!-- <div class="bar">
      Zhimeng Yin
    </div> -->
    <div class="bar">
      <div class="icon">
        Zhimeng Yin
      </div>
      <div class="else"></div>
    </div>
    <div class="other" v-if="screenWidth >= 1150">
      <div class="basic">
        <div class="info">
          <div class="head">Zhimeng Yin</div>
          <p>Assistant Professor</p>
          <p>Department of Computer Science</p>
          <p>City University of Hong Kong</p>
          <p>Email: yinzhimeng@gmail.com</p>
        </div>
        <div class="photo">
          <img src="./assets/unnamed.jpg"/>
        </div>    
      </div>
      <div class="interests">
        <div class="head2">Research Interests</div>
        <ul class="a">
          <li>Broad interest in cyber-physical systems (CPS) or Internet of Things (IoT), including the embedded, 
            wireless, and low-power sensor systems, mobile computing, localization, and wireless security.</li>
          <li>Focus on the intelligent and collaborative utilization of resources, including spectrum, 
            energy, and data, in heterogeneous wireless systems.</li>
        </ul>
      </div>
      <div class="cv">
        <div class="head2">CV</div>
        <div class="cvInfo">
          <div class="left">
            <ul class="a">
              <li>Ph.D. in Dept. of Computer Science & Engineering<br>
              University of Minnesota - Twin Cities (UMN), USA </li><br>
              <li>M.S. in Dept. of Electronics & Information Engineering<br>
              Huazhong University of Science and Technology, China </li><br>
              <li>B.S. in Dept. of Electronics & Information Engineering<br>
              Huazhong University of Science and Technology, China</li><br>
            </ul>
          </div>
          <div class="right">
            <ul class="b">
              <li>Sept. 2014 - Sept. 2020 <br> Advisor: Prof. Tian He </li><br>
              <li>Sept. 2011 - Mar. 2014 <br>  Advisor: Prof. Hongbo Jiang </li><br>
              <li>Sept. 2007 - Jun. 2011 </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="publications">
        <div class="head2">Publications</div>
        <div class="subTitle">
          Conferences
        </div>
        <div class="content">
          <ol class="c">
              <li>[ICDCS'20] <b>Zhimeng Yin</b>, Wenchao Jiang, Ruofeng Liu, Song Min Kim, and Tian He, "SafetyNet: Interference Protection via Transparent PHY Layer Coding", 
                accepted by 40th IEEE International Conference on Distributed Computing Systems.</li>
              <li>[MobiSys'18] <b>Zhimeng Yin</b>, Zhijun Li, Song Min Kim, and Tian He, "Explicit Channel Coordination via Cross-technology Communication", 
                in proceedings of 16th Annual International Conference on Mobile Systems, Applications, and Services.<a href="https://drive.google.com/open?id=1RByIdZSEoTK78UzfN8lWLzozZXDKdXTs" target="_blank">[PDF]</a></li>
              <li>[INFOCOM'17] <b>Zhimeng Yin</b>, Wenchao Jiang, Song Min Kim and Tian He, "C-Morse: Cross-technology communication with transparent Morse coding", 
                in Proc. of the IEEE International Conference on Computer Communications.<a href="https://drive.google.com/open?id=1WcCAkuzyttSE6Lvp5bljeQPSM2Vjubwi" target="_blank">[PDF]</a></li>
              <li>[INFOCOM'20] Zhuqing Xu, Junzhou Luo, <b>Zhimeng Yin</b>, Tian He, and Fang Dong, "S-MAC: Achieving High Scalability via Adaptive Scheduling in LPWAN", 
                in Proc. of the IEEE International Conference on Computer Communications.</li>
              <li>[INFOCOM'20] Weiwei Chen, <b>Zhimeng Yin</b> and Tian He, "Global Cooperation for Heterogeneous Networks", 
                in Proc. of the IEEE International Conference on Computer Communications.</li>
              <li>[SenSys'19] Ruofeng Liu, <b>Zhimeng Yin</b>, Wenchao Jiang, and Tian He, "LTE2B: Time-Domain Cross-Technology Emulation under LTE Constraints", 
                in Proc. of the 15th Conference on Embedded Network Sensor Systems.<a href="https://www.youtube.com/watch?v=ycOY9y__3bw" target="_blank">[DEMO]</a> <a href="https://drive.google.com/open?id=1YpToX-A5ObZi2xJMcViPcRtx3J21HXhi" target="_blank">[PDF]</a></li>
              <li>[ICNP'18] Shuai Wang, <b>Zhimeng Yin</b>, Zhijun Li, and Tian He, "Networking Support For Physical-Layer Cross-Technology Communication", 
                in Proc. of the 26th International Conference on Network Protocols.<a href="https://drive.google.com/open?id=10lJS-KC6DKc8JQIHiBv2gZq-RGYXZs9f" target="_blank">[PDF]</a></li>
              <li>[SenSys'17] Wenchao Jiang, <b>Zhimeng Yin</b>, Ruofeng Liu, Zhijun Li, Song Min Kim, and Tian He, "BlueBee: a 10, 000x Faster Cross-Technology Communication via PHY Emulation", 
                in Proc. of the 13th Conference on Embedded Network Sensor Systems.<a href="https://youtu.be/ZAtHBLRmEUs" target="_blank">[DEMO]</a> <a href="https://drive.google.com/open?id=1CxFDggwstEQVg81AMC-VYEF8v-X2Tanr" target="_blank">[PDF]</a></li>
              <li>[INFOCOM'17] Wenchao Jiang, <b>Zhimeng Yin</b>, Song Min Kim, and Tian He, "Transparent Cross-technology Communication over Data Traffic", 
                in Proc. of the IEEE International Conference on Computer Communications.<a href="https://drive.google.com/open?id=1cAvJAVZAXXz80_jEZkDIMsQgby4tth5h" target="_blank">[PDF]</a></li>
              <li>[ICNP'14] Shuai Wang, Song Min Kim, <b>Zhimeng Yin</b>, and Tian He,"Correlated Coding: Efficient Network Coding under Correlated Unreliable Wireless Links", 
                in Proc. of the 22nd International Conference on Network Protocols.<a href="https://drive.google.com/open?id=1Vtoev5SvDapNdgj0aG4OTU00pI2ki9UN" target="_blank">[PDF]</a></li>
              <li>[SIGMETRICS'13] Guang Tan, <b>Zhimeng Yin</b>, and Hongbo Jiang, "Trap array: a unified model for scalability evaluation of geometric routing", In ACM SIGMETRICS'13.<a href="https://drive.google.com/open?id=1rvgkNtoTgUhpQAOl6LV8cUIcuMy1xqiu" target="_blank">[PDF]</a></li>
          </ol>
        </div>
        <div class="subTitle">
          Journals
        </div>
        <div class="content">
           <ol class="c">
              <li>[TMC] Shuai Wang, <b>Zhimeng Yin</b>, Shuai Wang, Yongrui Chen, Zhijun Li, Song Min Kim, and Tian He, "Networking Support for Bidirectional Cross-technology Communication", 
                in the ACM Transactions on Mobile Computing.<a href="https://drive.google.com/open?id=1ZNxFwbUvGzFn3xNLFDEWsYF9BcpDGFNl" target="_blank">[PDF]</a></li>
              <li>[TON] Wenchao Jiang,<b> Zhimeng Yin</b>, Ruofeng Liu, Zhijun Li, Song Min Kim, and Tian He, "Boosting the Bitrate of Cross-Technology Communication on Commodity IoT Devices", 
                in the ACM/IEEE Transactions on Networking.<a href="https://drive.google.com/open?id=1oK5KF09qTre71BMFi_WtyifMXGKtzR0S" target="_blank">[PDF]</a></li>
              <li>[TON] Guang Tan, <b>Zhimeng Yin</b>, and Hongbo Jiang, "Trap Array: A Unified Model for Scalability Evaluation of Geometric Routing", 
                in the ACM/IEEE Transactions on Networking.<a href="https://drive.google.com/open?id=1L21ERP-1EgakU3GRfhPODdBbBVM3P7gz" target="_blank">[PDF]</a></li>
              <li>[TWC] Kechao Cai, <b>Zhimeng Yin</b>, Hongbo Jiang, Guang Tan, Peng Guo, Chonggang Wang, and Bo Li, "OnionMap: A Scalable Geometric Addressing and Routing Scheme for 3D Sensor Networks", 
                In IEEE Transactions on Wireless Communications.<a href="https://drive.google.com/open?id=1rfbfLE-o0wfsja_Q3kvWRr1p-hzaxT0D" target="_blank">[PDF]</a></li>
              <li>[TOSN] Shuai Wang, Song Min Kim, <b>Zhimeng Yin</b>, and Tian He, "Encode When Necessary: Correlated Network Coding Under Unreliable Wireless Links," 
                in the ACM Transactions on Sensor Networks.<a href="https://drive.google.com/open?id=1YciMa0ELFkdsV0kQLuUHVkZY0Z3oNwrb" target="_blank">[PDF]</a></li>
              <li>[TOSN] Guang Tan, Hongbo Jiang, Shengkai Zhang, <b>Zhimeng Yin</b>, Anne-Marie Kermarrec, "Connectivity-based and anchor-free localization in large-scale 2D/3D sensor networks", 
                in the ACM Transactions on Sensor Networks.<a href="https://drive.google.com/open?id=1QYTNNLqACyZDWgiJYCP0hC9beB1OVvcF" target="_blank">[PDF]</a></li>
          </ol> 
        </div>
      </div>
      <div class="demo">
        <div class="head2">BlueBee Demo</div>
        <div class="show">
           <div class="vedios">
                <iframe width="562" height="316" 
                src="https://www.youtube.com/embed/ZAtHBLRmEUs" frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen></iframe>
           </div>
           <div class="description">
              The cross-technology communication (CTC) is a promising technique proposed recently to bridge heterogeneous wireless technologies in the ISM bands. 
              Existing solutions use only the coarse-grained packet-level information for CTC modulation, suffering from a low throughput (e.g., 10 b/s). 
              BlueBee explores the PHY-layer information for CTC by emulating legitimate ZigBee frames with the Bluetooth radio, achieving dual-standard compliance and transparency. 
              Our implementation on both USRP and commodity devices shows that BlueBee can achieve standard ZigBee bit rate of 250 kb/s at more than 99% accuracy, 
              10000x faster than the start-of-the-art packet-level CTC technologies. 
           </div>
        </div>
        <div class="head2">LTE2B Demo</div>
        <div class="show">
          <div class="vedios">
                <iframe width="562" height="316" 
                src="https://www.youtube.com/embed/ycOY9y__3bw" frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen></iframe>
           </div>
           <div class="description">
              LTE2B enables WAN/WLAN devices, e.g., LTE smartphones and WiFi Access Points, 
              to directly transmit data to low-power IoT devices such as ZigBee and Bluetooth. 
              This is achieved via Time-domain Emulation that enables WAN/WLAN transmitters to accurately emulate the ZigBee/Bluetooth waveform. 
              We implement LTE2B on commodity devices (Nexus 5X smartphone and CC2530/CC1350 ZigBee/BLE SoC). 
              Extensive evaluation demonstrates that LTE2B achieves a robust (> 99% accuracy) and long distance (> 400 m) CTC performance under a full range of wireless configurations including indoor/outdoor, mobility, and duty-cycle settings. 
           </div>
        </div>
      </div>
    </div>
    <div class="otherSmall" v-else>
      <div class="basic">
        <div class="info">
          <div class="head">Zhimeng Yin</div>
          <p>Assistant Professor</p>
          <p>Department of Computer Science</p>
          <p>City University of Hong Kong</p>
          <p>Email: yinzhimeng@gmail.com</p>
        </div>
        <div class="photo">
          <img src="./assets/unnamed.jpg"/>
        </div>    
      </div>
      <div class="interests">
        <div class="head2">Research Interests</div>
        <ul class="a">
          <li>Broad interest in cyber-physical systems (CPS) or Internet of Things (IoT), including the embedded, 
            wireless, and low-power sensor systems, mobile computing, localization, and wireless security.</li>
          <li>Focus on the intelligent and collaborative utilization of resources, including spectrum, 
            energy, and data, in heterogeneous wireless systems.</li>
        </ul>
      </div>
      <div class="cv">
        <div class="head2">CV</div>
        <div class="cvInfo">
          <div class="left">
            <ul class="a">
              <li>Ph.D. in Dept. of Computer Science & Engineering<br>
              University of Minnesota - Twin Cities (UMN), USA </li><br>
              <li>M.S. in Dept. of Electronics & Information Engineering<br>
              Huazhong University of Science and Technology, China </li><br>
              <li>B.S. in Dept. of Electronics & Information Engineering<br>
              Huazhong University of Science and Technology, China</li><br>
            </ul>
          </div>
          <div class="right">
            <ul class="b">
              <li>Sept. 2014 - Sept. 2020 <br> Advisor: Prof. Tian He </li><br>
              <li>Sept. 2011 - Mar. 2014 <br>  Advisor: Prof. Hongbo Jiang </li><br>
              <li>Sept. 2007 - Jun. 2011 </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="publications">
        <div class="head2">Publications</div>
        <div class="subTitle">
          Conferences
        </div>
        <div class="content">
          <ol class="c">
              <li>[ICDCS'20] <b>Zhimeng Yin</b>, Wenchao Jiang, Ruofeng Liu, Song Min Kim, and Tian He, "SafetyNet: Interference Protection via Transparent PHY Layer Coding", 
                accepted by 40th IEEE International Conference on Distributed Computing Systems.</li>
              <li>[MobiSys'18] <b>Zhimeng Yin</b>, Zhijun Li, Song Min Kim, and Tian He, "Explicit Channel Coordination via Cross-technology Communication", 
                in proceedings of 16th Annual International Conference on Mobile Systems, Applications, and Services.<a href="https://drive.google.com/open?id=1RByIdZSEoTK78UzfN8lWLzozZXDKdXTs" target="_blank">[PDF]</a></li>
              <li>[INFOCOM'17] <b>Zhimeng Yin</b>, Wenchao Jiang, Song Min Kim and Tian He, "C-Morse: Cross-technology communication with transparent Morse coding", 
                in Proc. of the IEEE International Conference on Computer Communications.<a href="https://drive.google.com/open?id=1WcCAkuzyttSE6Lvp5bljeQPSM2Vjubwi" target="_blank">[PDF]</a></li>
              <li>[INFOCOM'20] Zhuqing Xu, Junzhou Luo, <b>Zhimeng Yin</b>, Tian He, and Fang Dong, "S-MAC: Achieving High Scalability via Adaptive Scheduling in LPWAN", 
                in Proc. of the IEEE International Conference on Computer Communications.</li>
              <li>[INFOCOM'20] Weiwei Chen, <b>Zhimeng Yin</b> and Tian He, "Global Cooperation for Heterogeneous Networks", 
                in Proc. of the IEEE International Conference on Computer Communications.</li>
              <li>[SenSys'19] Ruofeng Liu, <b>Zhimeng Yin</b>, Wenchao Jiang, and Tian He, "LTE2B: Time-Domain Cross-Technology Emulation under LTE Constraints", 
                in Proc. of the 15th Conference on Embedded Network Sensor Systems.<a href="https://www.youtube.com/watch?v=ycOY9y__3bw" target="_blank">[DEMO]</a> <a href="https://drive.google.com/open?id=1YpToX-A5ObZi2xJMcViPcRtx3J21HXhi" target="_blank">[PDF]</a></li>
              <li>[ICNP'18] Shuai Wang, <b>Zhimeng Yin</b>, Zhijun Li, and Tian He, "Networking Support For Physical-Layer Cross-Technology Communication", 
                in Proc. of the 26th International Conference on Network Protocols.<a href="https://drive.google.com/open?id=10lJS-KC6DKc8JQIHiBv2gZq-RGYXZs9f" target="_blank">[PDF]</a></li>
              <li>[SenSys'17] Wenchao Jiang, <b>Zhimeng Yin</b>, Ruofeng Liu, Zhijun Li, Song Min Kim, and Tian He, "BlueBee: a 10, 000x Faster Cross-Technology Communication via PHY Emulation", 
                in Proc. of the 13th Conference on Embedded Network Sensor Systems.<a href="https://youtu.be/ZAtHBLRmEUs" target="_blank">[DEMO]</a> <a href="https://drive.google.com/open?id=1CxFDggwstEQVg81AMC-VYEF8v-X2Tanr" target="_blank">[PDF]</a></li>
              <li>[INFOCOM'17] Wenchao Jiang, <b>Zhimeng Yin</b>, Song Min Kim, and Tian He, "Transparent Cross-technology Communication over Data Traffic", 
                in Proc. of the IEEE International Conference on Computer Communications.<a href="https://drive.google.com/open?id=1cAvJAVZAXXz80_jEZkDIMsQgby4tth5h" target="_blank">[PDF]</a></li>
              <li>[ICNP'14] Shuai Wang, Song Min Kim, <b>Zhimeng Yin</b>, and Tian He,"Correlated Coding: Efficient Network Coding under Correlated Unreliable Wireless Links", 
                in Proc. of the 22nd International Conference on Network Protocols.<a href="https://drive.google.com/open?id=1Vtoev5SvDapNdgj0aG4OTU00pI2ki9UN" target="_blank">[PDF]</a></li>
              <li>[SIGMETRICS'13] Guang Tan, <b>Zhimeng Yin</b>, and Hongbo Jiang, "Trap array: a unified model for scalability evaluation of geometric routing", In ACM SIGMETRICS'13.<a href="https://drive.google.com/open?id=1rvgkNtoTgUhpQAOl6LV8cUIcuMy1xqiu" target="_blank">[PDF]</a></li>
          </ol>
        </div>
        <div class="subTitle">
          Journals
        </div>
        <div class="content">
           <ol class="c">
              <li>[TMC] Shuai Wang, <b>Zhimeng Yin</b>, Shuai Wang, Yongrui Chen, Zhijun Li, Song Min Kim, and Tian He, "Networking Support for Bidirectional Cross-technology Communication", 
                in the ACM Transactions on Mobile Computing.<a href="https://drive.google.com/open?id=1ZNxFwbUvGzFn3xNLFDEWsYF9BcpDGFNl" target="_blank">[PDF]</a></li>
              <li>[TON] Wenchao Jiang,<b> Zhimeng Yin</b>, Ruofeng Liu, Zhijun Li, Song Min Kim, and Tian He, "Boosting the Bitrate of Cross-Technology Communication on Commodity IoT Devices", 
                in the ACM/IEEE Transactions on Networking.<a href="https://drive.google.com/open?id=1oK5KF09qTre71BMFi_WtyifMXGKtzR0S" target="_blank">[PDF]</a></li>
              <li>[TON] Guang Tan, <b>Zhimeng Yin</b>, and Hongbo Jiang, "Trap Array: A Unified Model for Scalability Evaluation of Geometric Routing", 
                in the ACM/IEEE Transactions on Networking.<a href="https://drive.google.com/open?id=1L21ERP-1EgakU3GRfhPODdBbBVM3P7gz" target="_blank">[PDF]</a></li>
              <li>[TWC] Kechao Cai, <b>Zhimeng Yin</b>, Hongbo Jiang, Guang Tan, Peng Guo, Chonggang Wang, and Bo Li, "OnionMap: A Scalable Geometric Addressing and Routing Scheme for 3D Sensor Networks", 
                In IEEE Transactions on Wireless Communications.<a href="https://drive.google.com/open?id=1rfbfLE-o0wfsja_Q3kvWRr1p-hzaxT0D" target="_blank">[PDF]</a></li>
              <li>[TOSN] Shuai Wang, Song Min Kim, <b>Zhimeng Yin</b>, and Tian He, "Encode When Necessary: Correlated Network Coding Under Unreliable Wireless Links," 
                in the ACM Transactions on Sensor Networks.<a href="https://drive.google.com/open?id=1YciMa0ELFkdsV0kQLuUHVkZY0Z3oNwrb" target="_blank">[PDF]</a></li>
              <li>[TOSN] Guang Tan, Hongbo Jiang, Shengkai Zhang, <b>Zhimeng Yin</b>, Anne-Marie Kermarrec, "Connectivity-based and anchor-free localization in large-scale 2D/3D sensor networks", 
                in the ACM Transactions on Sensor Networks.<a href="https://drive.google.com/open?id=1QYTNNLqACyZDWgiJYCP0hC9beB1OVvcF" target="_blank">[PDF]</a></li>
          </ol> 
        </div>
      </div>
      <div class="demo">
        <div class="head2">BlueBee Demo</div>
        <div class="show">
           <div class="vedios">
                <iframe width="562" height="316" 
                src="https://www.youtube.com/embed/ZAtHBLRmEUs" frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen></iframe>
           </div>
           <div class="description">
              The cross-technology communication (CTC) is a promising technique proposed recently to bridge heterogeneous wireless technologies in the ISM bands. 
              Existing solutions use only the coarse-grained packet-level information for CTC modulation, suffering from a low throughput (e.g., 10 b/s). 
              BlueBee explores the PHY-layer information for CTC by emulating legitimate ZigBee frames with the Bluetooth radio, achieving dual-standard compliance and transparency. 
              Our implementation on both USRP and commodity devices shows that BlueBee can achieve standard ZigBee bit rate of 250 kb/s at more than 99% accuracy, 
              10000x faster than the start-of-the-art packet-level CTC technologies. 
           </div>
        </div>
        <div class="head2">LTE2B Demo</div>
        <div class="show">
          <div class="vedios">
                <iframe width="562" height="316" 
                src="https://www.youtube.com/embed/ycOY9y__3bw" frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen></iframe>
           </div>
           <div class="description">
              LTE2B enables WAN/WLAN devices, e.g., LTE smartphones and WiFi Access Points, 
              to directly transmit data to low-power IoT devices such as ZigBee and Bluetooth. 
              This is achieved via Time-domain Emulation that enables WAN/WLAN transmitters to accurately emulate the ZigBee/Bluetooth waveform. 
              We implement LTE2B on commodity devices (Nexus 5X smartphone and CC2530/CC1350 ZigBee/BLE SoC). 
              Extensive evaluation demonstrates that LTE2B achieves a robust (> 99% accuracy) and long distance (> 400 m) CTC performance under a full range of wireless configurations including indoor/outdoor, mobility, and duty-cycle settings. 
           </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      screenWidth:''// Monitoring the width and when it is less than 1150px, the site would be reloaded.
    };
  },
  mounted(){
    this.screenWidth = document.body.clientWidth;
    window.onresize = () => {
        return (() => {
          this.screenWidth = document.body.clientWidth;
        })();
    }
  }
}
</script>

<style>
/* #app{
  padding: 0;
  margin:0 ;
} */
/* body{
  background-size: 100%;
} */
.bar{
  position: fixed;
  top: 0px;
  left: 0px;
  display: flex;
  flex-direction: row;
  width: 100%;
}
.icon{
  display: flex;
  width: 180px;
  color: aliceblue;
  background-color:rgb(4, 25, 83);
  padding-top: 10px;
  padding-bottom: 10px;
  display:inline;
  font-size: 25px;
  text-align: center;
  font-family: 'Times New Roman', Times, serif;
}
.else{
  display: flex;
  background-color: rgb(5, 73, 122);
  width: calc(100% - 180px)
  /* margin-right: 0px; */
}
.other{
  display:flex;
  width:1150px;
  padding-top: 105px;
  flex-direction: column;
  margin:0 auto;
  /* background-color: antiquewhite; */
}
.otherSmall{
  display:flex;
  width:100%;
  padding-top: 105px;
  flex-direction: column;
  margin:0 auto;
}
.basic{
  display: flex;
  flex-direction: row;
}
.info{
  width: 70%;
}
.photo{
  /* background-color: aquamarine; */
  width: 30%;
}
img{
  width: 50%;
  margin-left: 30%;
  margin-top: 5%;
}
.head{
  color:rgb(8, 53, 177);
  font-size:25px ;
  padding-bottom: 18px;
}
.head2{
  color:rgb(8, 53, 177);
  font-size:25px ;
  padding-bottom: 7px;
}
.interests{
  margin-top: 45px;
}
ul.a{
  list-style-type:square;
  margin-top: 0px;
  padding-left: 18px;
  font-size: 14px;
  line-height: 25px;
  padding-bottom: 10px;
}
ul.b{
  list-style-type:none;
  margin-top: 0px;
  padding-left: 18px;
  font-size: 14px;
  line-height: 25px;
}
.cv{
  margin-top: 45px;
}
.cvInfo{
  display: flex;
  flex-direction: row;
}
.left{
  width: 70%;
  /* background-color: aquamarine; */
}
.publications{
  margin-top: 45px;
}
.subTitle{
  font-size: 20px;
  padding-top: 3px;
}
ol.c{
  margin-top: 0px;
  padding-left: 26px;
  font-size: 14px;
  line-height: 25px;
}
.demo{
  margin-top: 45px;
}
.show{
  margin-bottom: 45px;
  display: flex;
  flex-direction: row;
}
.vedios{
  display: flex;
  width: 50%;
  /* background-color: brown; */
}
.description{
  display: flex;
  margin-top: 15px;
  margin-left: 15px;
  /* background-color: cadetblue; */
  width: 50%;
}
a:link {color:rgb(8, 53, 177);}      /* 未访问链接*/
a:visited {color:rgb(8, 53, 177);}  /* 已访问链接 */
a:hover {color:rgb(8, 53, 177);}  /* 鼠标移动到链接上 */
a:active {color:rgb(8, 53, 177);}  /* 鼠标点击时 */
</style>
