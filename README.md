pip install streamlit

import streamlit as st
import pandas as pd 
import plotly.express as px

df = px.data.iris()
df 
x = 10
'x =', x 
st.write("何でも書ける")
