# TOPSIS-python3
This python code saves "ordered.csv" file containing a extra column of Rank in current working directory.<br/>PyPI Project link <a href = "https://pypi.org/project/topsis-csv-python3/1.0.1/">here</a> 
<H2>TOPSIS</H2>
Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) originated in the 1980s as a multi-criteria decision making method. TOPSIS chooses the altenrative of shortest Euclidean distance from the idael solution, and fartherst distance from the negative-ideal solution.
<H2>Usage</H2>
Use below commands to install and use
<ul>
  <li><b>pip install topsis-csv-python3==1.0.1</b></li>
  <li><b>python3</b></li>
>>>from topsis import topsis<br/>
>>>t = topsis.topsis([filename],[weights],[imapcts])
 </ul>
 e.g. t = topsis.topsis("data.csv","1,2,1,1","-,+,+,+")
