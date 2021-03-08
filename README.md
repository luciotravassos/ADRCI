# ADRCI
O adrci é uma ferramenta de analise de logs do banco de dados Oracle
ADRCI
 
 1. MOSTRANDO O ALERT - SHOW ALERT / show alert tail 20
 2. MOSTRANDO ERROS - SHOW PROBLEM
 3. MOSTRANDO FALHAS - SHOW INCIDENT
 4. MOSTRANDO TRACES - SHOW TRACEFILE ou show trace /u01/app/oracle/diag/rdbms/td215/TD215/trace/TD215_j000_15102.tr
 5. MOSTRANDO CONTRUDO DO TRACE - SHOW TRACE FILE PATH_DO_TRACE
 6. MOSTRANDO OS HOMES = show homes
 7. SETANDO OS HOMES = set home diag/rdbms/td215/TD215
 8. MOSTRANDO INCIDENTE COM DETALHES = show incident -mode detail ou show incident -mode detail -p "INCIDENT_ID=1362971"
 9. Gerenciando traces = set control (SHORTP_POLICY = 240) e set control (LONGP_POLICY = 720)
 10. Mostrando detalhes = show control 
 11. Limpando traces manualmente = purge -age 10 -type TRACE / purge -age 30 -type TRACE
 12. ADRCI EXEC="SHOW HOMES; SHOW INCIDENT"
 14. SET HOMEPATH diag/rdbms/orcl/orcl; SHOW ALERT -term
 15. ADRCI EXEC="SHOW HOMES"
