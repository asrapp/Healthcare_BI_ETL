# Healthcare_BI_ETL
An automated ETL pipeline for processing healthcare survey data, analyzing patient satisfaction and operational metrics, and visualizing insights through PostgreSQL and interactive dashboards

# ETL Pipeline Project for Healthcare Analytics

This project demonstrates an ETL pipeline for splitting and processing healthcare survey data. 
It automates data extraction, transformation, and loading into PostgreSQL using Python.

## Features
- Data cleaning and splitting
- PostgreSQL integration
- Automated ETL pipeline

## Try it in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your_username/your_repo_name/blob/main/etl_project.ipynb)

## Dataset
The data comes from healthcare patient survey responses. See the [dataset source](link_to_dataset) for more details.

## Requirements
- Python 3.8+
- pandas
- psycopg2
- SQLAlchemy

## Interactive Tableau Dashboard
[![Dashboard Preview](dashboard_preview.png)](<div class='tableauPlaceholder' id='viz1732678019041' style='position: relative'><noscript><a href='#'><img alt='Health Care BI ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;he&#47;healthcar_BI&#47;HealthCareBI&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='views&#47;healthcar_BI&#47;HealthCareBI?:language=en-US&amp;:embed=true&amp;publish=yes&amp;:sid=&amp;:redirect=auth' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;he&#47;healthcar_BI&#47;HealthCareBI&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1732678019041');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1427px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>)

Click the image above to view the interactive dashboard on Tableau Public.


