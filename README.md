<dl>
  <h1> Comparison: Convolution, Involution, CondConv </h1>
  <p>The traditional architecture of the Convolution Neural Network (CNN) has been one of the most common and powerful neural networks, especially for dealing with image information. However, some of its shortcomings, such as redundant filters and parameters, are believed to exist, contributing to unnecessary computation, and reducing the efficiency of the network. Dynamic neural networks, on the other hand, provide a more flexible architecture based on different samples. </p>
  <p>In this report, traditional Convolution as well as the other two pixel-wise dynamic networks, specifically, Involution and Conditionally Parameterized Convolutions (CondConv), are introduced. An experiment will be conducted on the dataset Cifar-10 to compare the efficiency and performance of distinct networks. </p>
  <p> Find the three text files appended to view more results.</p>
  <h2>Cifar-10</h2>
  <p>Cifar-10 is a ten-class image dataset with 60,000 pictures. Each image is in size of 28x28 with 3 channels, and each of the class has 6,000 samples.</p>
  <img src="img/Picture3.png" height=400/>
  <h2>Convolution</h2>
  <p> ResNet18 is used. </p>
  <img src="img/Picture1.png" height=200/>
  <h2>Involution</h2>
  <p> We adjust ResNet18 by replacing the second layer of each basic block to be an Involution layer. </p>
  <img src="img/Invo Diagram.drawio.png" height=200/>
  <h2>Convolution</h2>
  <p> We adjust ResNet18 by replacing the second layer of each basic block to be an CondConv layer. </p>
  <img src="img/condconv Diagram.drawio.png" height=200/>
  <h2>Result</h2>
  <img src="img/Screenshot 2021-12-21 010211.png" height=300/>
</dl>
