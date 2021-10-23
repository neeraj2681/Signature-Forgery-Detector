# Signature-Forgery-Detector

Detects if a given handwritten signature is authentic or not

For a given handwritten signature, the model tries to depict the class(either forged or genuine) based on the training phase.
The dataset contains 54 signatures for each of 160 people out of which first 30 signatures are forged and the next 24 signatures are genuine.

<b>The training and testing is done in 70:30 ratio. </b>
<h3>Results</h3>
<ul>
  <li>Testing accuracy for MLP comes out to be around 57%</li>
  <li>Testing accuracy for MLP along with 2 layers of CNN comes out to be 78%</li>
</ul>


