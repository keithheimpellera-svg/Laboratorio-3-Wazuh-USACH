\# Dimensionamiento de Wazuh



\## Escenario 1



\- EPS: 200

\- Tamaño estimado por evento: 700 bytes

\- Factor de overhead: 1

\- Factor de almacenamiento: 0,35

\- Retención: 90 días



Cálculo:



200 × 700 × 1 × 0,35 ≈ 4 GB/día



Para 90 días:



4 GB × 90 ≈ 360 GB



Resultado aproximado: 4 GB/día y 360 GB para 90 días.



\## Escenario 2



\- EPS: 3.000

\- Tamaño estimado por evento: 700 bytes

\- Factor de overhead: 2

\- Factor de almacenamiento: 0,35

\- Retención: 90 días



Cálculo:



3000 × 700 × 2 × 0,35 ≈ 118 GB/día



Para 90 días:



118 GB × 90 ≈ 10,6 TB



Resultado aproximado: 118 GB/día y 10,6 TB para 90 días.

