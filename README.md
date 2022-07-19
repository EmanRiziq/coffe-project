# coffe-project
 
change(let formEl = document.getElementById("formID");) to (let formEl = document.getElementById("formID"))


in renderTable method
change (tr.appendChild(priceTD);) to ( tr.appendChild(priceTd);)


in renderAll function:
change (for (let i = 0; i <= allDrinks.length; i++)) to (for (let i = 0; i < allDrinks.length; i++) )

the hot choclet and mocha images are the same, I don't know if it was intentional or by mistake 


renderAll function was called txice thats why the output is dublicate, so i remove the call in line 91