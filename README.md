## Welcome to GitHub Pages

<html>
<body>

<input type="text" id="att1" value="Some text...">

<input type="text" id="att2" value="Some text...">

<input type="text" id="att3" value="Some text...">

<input type="text" id="att4" value="Some text...">

<input type="text" id="att5" value="Some text...">

<input type="text" id="att6" value="Some text...">

<input type="text" id="att7" value="Some text...">

<input type="text" id="att8" value="Some text...">

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  var x = document.getElementById("myText").value;
  document.getElementById("demo").innerHTML = x;
}
</script>

<script>
package com.mycompany.mavenproject2;
 
import java.util.logging.Level;
import java.util.logging.Logger;
import weka.classifiers.Classifier;
import weka.classifiers.evaluation.Evaluation;
import weka.classifiers.functions.MultilayerPerceptron;
import weka.core.Instances;
import weka.core.SerializationHelper;
import weka.core.converters.ConverterUtils.DataSource;

import java.util.ArrayList;
import weka.core.Attribute;
import weka.core.DenseInstance;
import weka.filters.Filter;
import weka.filters.unsupervised.attribute.Normalize;

String rootPath="/Users/athan/Desktop/WP"; 
Classifier cls = (Classifier) weka.core.SerializationHelper.read(rootPath+"model1.model");

Instances originalTrain= //load or create Instances to predict

int s1=0;  

double value=cls.classifyInstance(originalTrain.instance(s1));

String prediction=originalTrain.classAttribute().value((int)value); 

System.out.println("The predicted value of instance "+
                    Integer.toString(s1)+
                    ": "+prediction); 
</script>

</body>
</html>

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
