**Aleksandr Kalatalo**

phone: +375-44-721-14-50 (A1); email: *fsmf@yandex.by*;    Telegram: *warshoo*;    Discord: *warshoo*;    Skype: *alihandro.lopez*;

For me is important to understand, can I learning via self-education and online,my goal is to became a FrontEnd junior developer.

Now I am in process self-education.

I successfully finished Sukhoi State Technical University of Gomel with diploma “electronic engineer”.

My English lanquage level is B1+ , it was cheked with *https://www.efset.org/ru/* test.

Now I am just trying to make some scripts, the fragment of my code is below:

```
let Mass_Koeff = [mkoef1,mkoef2,mkoef3,mkoef4];//--------------------------массив коэффициэнтов, которыми будет определяться напряжение
//каждой ячейки
let result_voltage_array = [];
//-----------------------------------------------------------------------описание f. для получения rnd значения для определения (ind)
function getRandomArbitrary(min, max) {
    return Math.random() * (max - min) + min;
  }

//-----------------------------------------------------------------------описание f. напряжений ячеек для отдельно взятого часа
function resCellVoltages(Cell_Voltage_Index, Sum_Volt){
  let result = [];
    for(let i = 0; i < 4; i++ ){
      result[i] = Cell_Voltage_Index[i] * Sum_Volt;
      result[i] = result[i].toFixed(2);
      
    }
    
  return(result);
 }


  const ind = Math.floor(getRandomArbitrary(0,5));//---------------------определение (ind)
 
  

  

for (let t = 0; t < Summary_Voltage_Array.length; t++ ){//----------------цикл расчета напряжений для каждого часа

 let some_array = resCellVoltages(Mass_Koeff[ind],Summary_Voltage_Array[t]);

 result_voltage_array[t] = some_array ;
}
```

