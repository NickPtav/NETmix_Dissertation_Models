Os modelos forma escolhido de acordo com parâmetros relevantes na modelagem do processo.
No trabalho de Laranjeiras "NETmix static mixer , modeling CFD simulation and Experimental Characterisation), 2005, ele apresentou a modelagem do reator.

Entre os fatores, a relação entre volume de canal e volume do reator é importante para a importância de mistura, chamado "segregação", pois basicamente a mistura no reator ocorre dentro das camaras, enquanto nos canais não há mistura, ou seja, quanto maior o volume dos canais em relação ao volume do reator, pior será a mistura. 

 $α = Vchannel / Vnetwork$

Outros fator é o a razão entre diâmetro das camaras e diâmetro dos canais:
Essa razão deve estar preferencialmente entre 6 e 7, de acordo com o trabalho de patente [0101] " to maximize the mixing intensity in the chambers of the structured network, the ratio of the chamber diameter to the channel width is preferably 6 to 6. 

$α = Dchamber / Dchannel$

E claro, observar o número de Reynolds:
"For better results, the Reynolds number Re is larger then 100, preferably larger than 150. 

$Re = ρ . v . d / μ$

Foi feito uma análise dos tipos de modelos possíveis, e 18 modelos foram escolhidos com a realização de algumas modificações que vão impactar na discussão do trabalho. 
Os calculos e resultados estão na pasta "Volume_calculation"

MODELOS SEM CANAIS HORIZONTAIS
|I	|c_h (mm)|	r_p (mm)|	num_rows	|num_columns|	r_d (mm)|	extr (mm)|	Volume (mm^3)|	Vol_ratio|	cc_ratio|
|----------|----------|----------|----------|----------|----------|----------|----------|-----------|------|
|93	|1.625|	3.50|	10|	6|	3.5|	3|	13494.495639|	0.101662|	4.307692|
|21	|0.875	|2.25	|20	|6	|3.5	|3	|19460.100295	|0.142161	|5.142857|
|11	|0.875	|2.00	|30	|6	|3.5	|3	|28132.473672	|0.163721	|4.571429|
|107	|1.250	|3.75	|10	|6	|3.5	|3	|14015.699879	|0.061940	|6.000000|
|51	|0.875	|2.75	|20	|6	|3.5	|3	|21786.175287	|0.103970	|6.285714|
|71	|0.875	|3.00	|30	|6	|3.5	|3	|35084.053632	|0.087651	|6.857143|
|106	|0.875	|3.75	|10	|6	|3.5	|3	|13746.534824	|0.043572	|8.571429|
|65	|0.500	|3.00	|20	|6	|3.5	|3	|22290.524512	|0.051308	|12.000000|
|101|	0.875	|3.50	|30	|6	|3.5	|3	|39833.966577	|0.058030	|8.000000|

MODELOS COM CANAIS HORIZONTAIS
|I	|c_h (mm)|	r_p (mm)|	num_rows	|num_columns|	r_d (mm)|	extr (mm)|	Volume (mm^3)|	Vol_ratio|	cc_ratio|
|----------|----------|----------|----------|----------|----------|----------|----------|-----------|------|
|93	|1.625|	3.50|	10|	6|	3.5|	3|	15378.193806|	0.089209	4.307692|
|21	|0.875	|2.25	|20	|6	|3.5	|3	|22156.676987	|0.124859	|5.142857|
|11	|0.875	|2.00	|30	|6	|3.5	|3	|32436.461359	|0.141997	|4.571429|
|107	|1.250	|3.75	|10	|6	|3.5	|3	|15389.446819	|0.056411	|6.000000|
|51	|0.875	|2.75	|20	|6	|3.5	|3	|24282.208621	|0.093282	|6.285714|
|71	|0.875	|3.00	|30	|6	|3.5	|3	|38775.753237	|0.079306	|6.857143|
|106	|0.875	|3.75	|10	|6	|3.5	|3	|14704.467158		|0.040734	|8.571429|
|65	|0.500	|3.00	|20	|6	|3.5	|3	|23656.304198	|0.048346	|12.000000|
|101|	0.875	|3.50	|30	|6	|3.5	|3	|43220.233317		|0.053483	|8.000000|
