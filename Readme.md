# JSONs para la extraccion de informacion acerca del Sistema Electrico Nacional (SEN)


### El JSON queda asi (Tambien puede verlo en el archivo Plantilla_SEN v2.json):

```json
{
    "zones_with_problems": ["west" , "middle", "east"], 
    "date": "YYmmdd",
    "url": "", 
    "prediction": {
        "availability": ,  
        "demand_max": ,
        "impact": ,
        "deficit": ,
        "backup": 
    },
    "morning_info": {
        "time": "HHmm",
        "availability": , 
        "demand": , 
        "deficit": 
    },
	
    "broken": {
        //Format: "<CTE_ID>": [<Patana(Unity)>], Example: "AG": [1,2], "MG": [5,6]
        },
    "maintenance": {
        //Format: "<CTE_ID>": [<Patana(Unity)>], Example: "AG": [1,4]
    },
    "limitations": ,
        
    "distributed": {
        "motors_with_problems": ,
        "total_impact": ,
        "combustible_problems": ,
        "ships_with_problems": ,
        "motors_impact": 
    },
    "impact": {
        "total_hours": "HHmm",
        "max": ,
        "max_hour": "HHmm"
    }
}
```

<!-- http://www.cubadebate.cu/noticias/2024/02/12/?s=afectacion -->