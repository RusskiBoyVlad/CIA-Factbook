# CIA-Factbook

Notes for SQL in Jupyter:
- To run ipython-sql run this command i nocde tell of jupyter beforehand (just once)
  !conda install -yc conda-forge ipython-sql
    
.DB file found here: https://dsserver-prod-resources-1.s3.amazonaws.com/257/factbook.db

The following 3 lines 
%%capture - captures the stfout/stderr of a cell
%load_ext sql - loads ipython-sql  (5th line)
%sql sqlite:///factbook.db - opens the .db file
