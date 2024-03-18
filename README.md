import streamlit as st
import pandas as pd

voc=pd.read_csv('https://docs.google.com/spreadsheets/d/1jH6kJJISFA0Ye4gE4CzG7ZEjBJhCRelGOZN-HnxyZBQ/edit?pli=1#gid=0')
st.dataframe(voc)
l=voc.shale[0]
i=hp.random.choice(range(l))
word_fr=voc['definition'].values[i]
word_chi=voc[''].values[i]
st. write(word_fr+""+word_chi)
