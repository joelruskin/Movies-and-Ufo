#!/usr/bin/env python
# coding: utf-8

# In[1]:


import pandas as pd
import numpy as np


# In[2]:


movies=pd.read_csv('http://bit.ly//imdbratings')


# In[3]:


movies.head()


# In[4]:


movies.describe()


# In[5]:


len(movies)


# In[7]:


movies


# In[8]:


movies_1=movies.sample(frac=0.75,random_state=1234)


# In[9]:


movies_1


# In[10]:


movies_2=movies.drop(movies_1.index)


# In[11]:


movies_2


# In[12]:


245+734


# In[14]:


movies_1.index.sort_values()


# In[16]:


movies_2.index.sort_values()


# In[25]:


movies.duration.unique()


# In[23]:


movies=pd.DataFrame[(genre=="Action")]|[(genre=="Family")]|[(genre=="Drama")].head()


# In[26]:


counts=movies.genre.value_counts()


# In[27]:


counts


# In[28]:


counts1=movies.content_rating.value_counts()


# In[30]:


counts1


# In[31]:


counts.nlargest(3)


# In[32]:


counts.nsmallest(3)


# In[34]:


movies=pd.read_csv("http://bit.ly//imdbratings")


# In[35]:


movies


# In[71]:


movies.sum


# In[37]:


movies.head()


# In[38]:


movies.describe()


# In[41]:


movies1=movies.sample(frac=0.75,random_state=1234)


# In[43]:


movies1


# In[45]:


movies2=movies.drop(movies1.index)


# In[46]:


movies2


# In[49]:


movies.genre.unique()


# In[53]:


counts=movies.genre.value_counts()


# In[54]:


counts


# In[61]:


counts1=counts.nlargest(3)


# In[62]:


counts1


# In[63]:


ufo=pd.read_csv("http://bit.ly//uforeports")


# In[64]:


ufo


# In[65]:


ufo.head()


# In[66]:


ufo.isna().sum()


# In[72]:


ufo.isna().mean()


# In[73]:


ufo.dropna(axis=1).head()


# In[ ]:




