Description
-----------
List of surgical tool datasets organised by task.

Tool classification
-------------------

<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Paper</td>
  </tr>
  
  <!-- Cholec80 -->
  <tr>
    <td align="center">
      <a href="http://camma.u-strasbg.fr/datasets">Cholec80</a>
    </td>
    <td align="center">
      80 videos of cholecystectomy surgeries performed by 13 surgeons. The videos are captured at 25 fps. The dataset is labeled with the phase (at 25 fps) and tool presence annotations (at 1 fps). A tool is defind as present in an image if at least half of the tool tip is visible.
    </td>
    <td align="center">
      <a href="https://arxiv.org/abs/1602.03012">Twinanda et al. 2016</a>
    </td>
  </tr>
  
</table>

Tool segmentation
-----------------
<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Paper</td>
  </tr>
  
  <!-- EndoVis2015 -->
  <tr>
    <td align="center">
      <a href="https://opencas.webarchiv.kit.edu/?q=node/30">EndoVis2015</a>
    </td>
    <td align="center">
      40 2D in-vivo images from 4 laparoscopic colorectal surgeries. Each pixel is labelled as either background, shaft and manipulator (~160 2D images and annotations in total). 4x 45-second 2D images sequences of at least one Large Needle Driver instrument in an ex-vivo setup. Each pixel is labelled as either backgroud, shaft, head or clasper. 
    </td>
    <td align="center">
      N/A
    </td>
  </tr>
  
  <!-- EndoVis2017 -->
  <tr>
    <td align="center">
      <a href="https://endovissub2017-roboticinstrumentsegmentation.grand-challenge.org">EndoVis2017</a>
    </td>
    <td align="center">
      8x 225-frame robotic surgical videos, captured at 2 Hz, with manually labelled different tool parts and types. The testing set contains 8x 75-frame videos and 2x 300-frame videos.
    </td>
    <td align="center">
      <a href="https://arxiv.org/pdf/1902.06426.pdf">Allan et al. 2019</a>
    </td>
  </tr>
  
  <!-- EndoVis2018 -->
  <tr>
    <td align="center">
      <a href="https://endovissub2018-roboticscenesegmentation.grand-challenge.org">EndoVis2018</a>
    </td>
    <td align="center">
      Training dataset is made up of 16 robotic nephrectomy procedures recorded using da Vinci Xi systems in porcine labs (subsampled to 2fps). Sequences with little or no motion are manually removed to leave 149 frames per procedure. Video frames are 1280x1024 and we provide the left and right eye camera image as well as the stereo camera calibration parameters. Labels are only provided for the left image. 
    </td>
    <td align="center">
      <a href="https://arxiv.org/abs/2001.11190">Allan et al. 2020</a>
    </td>
  </tr>
  
  <!-- RoboTool -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn22427422">RoboTool</a>
    </td>
    <td align="center">
      514 images extracted from the videos of 20 freely available surgical procedures and annotated for binary tool-background segmentation.
    </td>
    <td align="center">
      <a href="https://arxiv.org/abs/2102.09528">Garcia-Peraza-Herrera et al. 2021</a>
    </td>
  </tr>
  
  <!-- ROBUST-MIS 2019 -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn20575265">ROBUST-MIS2019</a>
    </td>
    <td align="center">
      Procedures in rectal resection and proctocolectomy. A training case encompasses a 10 second video snippet in form of 250 endoscopic image frames and a reference annotation for the last frame. In the annotated frame a “0” indicates the absence of a medical instrument and numbers “1”, “2“, ... represent different instances of medical instruments.
    </td>
    <td align="center">
      <a href="https://arxiv.org/abs/2003.10299">Ross et al. 2020</a>
    </td>
  </tr>
  
  <!-- CholecSeg8k -->
  <tr>
    <td align="center">
      <a href="https://www.kaggle.com/newslab/cholecseg8k">CholecSeg8k</a>
    </td>
    <td align="center">
      This dataset contains 8080 laparoscopic cholecystectomy image frames extracted and annotated from 17 video clips in Cholec80.
    </td>
    <td align="center">
      <a href="https://arxiv.org/pdf/2012.12453.pdf">Hong et al. 2020</a>
    </td>
  </tr>
  
</table>
