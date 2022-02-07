**Linear Voltage Regulator:** 

Regulator Used: **LM340T-5.0/NOPB**

What the design is? 

The type of circuit used for this design is a standard setup in order to ensure that the linear regulator used will not over heat or be disrupted by noise. 
A bulk capacitor is used to keep the output voltage stable when a high demand is needed. A bypass capacitor is used to filter AC noise. 
This type of setup is what is called a fixed setup. This is because no matter want the input voltage is the resulting output voltage will be always a contant value. 
Disclaimer these types of regulators are not efficient. 

What is the datasheet used? 

https://www.distrelec.biz/Web/Downloads/xx/_e/krLM340-LM78xx_e.pdf?mime=application%2Fpdf&src-supplier=Distrelec

**Adjustable Voltage Linear Regulator:** 

Regulator Used: **LM317AHVT**

What the design is? The type of circuit used for this design is a standard setup from the datasheet of the manufacturer. 
It consists of bulk and bypass capacitors as well as an adjustable potentiometer/rheostat in order to vary the output voltage of the system. 

What is the datasheet used? 

https://www.onsemi.com/pdf/datasheet/lm317ahv-d.pdf

**Useful Information:** 

How to import the design into a new diptrace schematic? 

Since I am using Altium designer I will list the steps for how to use it in DipTrace & Altium Designer. 

**DipTrace:** 

Step 1: Open up schematic capture. 

Step 2: File --> Import --> DipTrace ASCII --> Click File --> Open 

Step 3: File will be imported into schematic editor 

**Altium Designer:** 

Step 1: Open new schematic 

Step 2: File --> Import --> DXF/DWG --> Click File --> Open 

Step 3: File will be imported into Project.
