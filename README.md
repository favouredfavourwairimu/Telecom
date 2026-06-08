import numpy as np
import pandas as pd
hourly_traffic=[45,56,79,138,130,453,34]
for index, traffic in enumerate(hourly_traffic):
hour_number=index+1
if traffic>=100:
  print(f"hour{hour_number}: CRITICAL TRAFFIC!")
else :
  print(f"hour {hour_number}: TRAFFIC NORMAL")
