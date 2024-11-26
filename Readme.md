# JSONs para la extraccion de informacion acerca del Sistema Electrico Nacional (SEN)


### El JSON queda asi (Tambien puede verlo en el archivo Plantilla_SEN v2.json):

```json
{
    "zones_with_problems": ["west" , "middle", "east"], 
    "date": "", //Format: "YYmmdd", Example: "20240812"
    "url": "", 
    "prediction": {
        "availability": ,  
        "demand_max": ,
        "impact": ,
        "deficit": ,
        "backup": 
    },
    "morning_info": {
        "time": "", //Format: "HHmm", Example: "0730"
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
        "combustible_problems": , // that mean centrales de generación distribuida with fuel problems
        "ships_with_problems": , // that mean patanas with problems
        "motors_impact": 
    },
    "impact": {
        "total_hours": //Format: "HHmm", Example: "0730",
        "max": ,
        "max_hour": //Format: "HHmm", Example: "0730" 
    }
}
```

<!-- http://www.cubadebate.cu/noticias/2024/02/15/?s=afectacion -->