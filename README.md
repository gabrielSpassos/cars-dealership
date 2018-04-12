# Gym_service

_College project_

## Group 
 - Gabriel Santos dos Passos
 - Lucas Reis
 - Eduardo Amroginski

## Objectives

* Create CRUD of users
* Use MongoDb as database
* Create back-end with node
* Create front 
* User can create their own trainings

### Initial Model 

```javascript
{
  "nome": "Gabriel",
  "peso": 85,
  "altura": 1.83,
  "imc": 24.78,
  "matricula" : "123456789",
  "plano":{
    "modalidade": "semestral",
    "mensalidade": 110.90
  },
  "treinos":[
    {
      "nomeTreino":"Treino de Peitoral",
      "exercicios":[
        {
          "nomeExercicio":"supino reto",
          "peso": 25,
          "repeticoes": 12,
          "series" : 3,
          "descanco" : "60s"
        },
        {
          "nomeExercicio":"voador",
          "peso": 50,
          "repeticoes": 10,
          "series" : 4,
          "descanco" : "30s"
        }
      ]
    },
    {
      "nomeTreino":"Treino de Costas",
      "exercicios":[
        {
          "nomeExercicio":"Barra Supinada",
          "peso": 0,
          "repeticoes": 12,
          "series" : 3,
          "descanco" : "90s"
        },
        {
          "nomeExercicio":"remada",
          "peso": 50,
          "repeticoes": 10,
          "series" : 4,
          "descanco" : "45s"
        }
      ]
    }
  ]
}
```
