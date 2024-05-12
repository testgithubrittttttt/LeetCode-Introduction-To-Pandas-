import pandas as pd

def meltTable(report: pd.DataFrame) -> pd.DataFrame:
    result=pd.melt(report,id_vars=['product'],var_name='quarter',value_name='sales')
    return result
