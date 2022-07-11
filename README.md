<h1 align="center">
Hi, I'm Vincent!

<p align="center">
  <a href="https://github.com/VincentGarc"><img src="https://readme-typing-svg.herokuapp.com?lines=Corporate+Lawyer;Data+Science+Student;Python+Developer;DS%20|%20AI%20|%20ML%20Enthusiastic;Always%20learning%20new%20things&center=true&width=380&height=45"></a>
</p></h1>


```python

import pandas as pd

Vincent = [{
    'pronouns': ['He', 'His'],
    'code': ['Python', 'HTML', 'CSS', 'SQL'],
    'tools': ['Mongo', 'MySQL', 'PostgreSQL', 'Jupyter Notebook', 'Pycharm', 'GitHub', 'Excel'],
    'areas': ['Data', 'Data Analysis', 'Project Development', 'Fraud Detection', 'Administration'],
    'libraries': ['Pandas', 'Numpy', 'Tkinter', 'Matplotlib', 'Seaborn'],
    'others':    ['Mexican laws', 'Photography', 'Painting', 'Photoshop']
},
    {
        'py_soon': ['Sklearn', 'Keras', 'Tensorflow', 'ScyPy', 'Pytorch'],
        'learning': ['C#', 'Java'],
    }
]

today = pd.DataFrame([[key, vinc[0][key]] for key in vinc[0].keys()], columns=['Name', 'List'])
print(today)

tomorrow = pd.DataFrame([[key, vinc[1][key]] for key in vinc[1].keys()], columns=['Name', 'List'])
print(tomorrow)

```
