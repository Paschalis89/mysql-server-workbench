entrare nel contenitore  docker con i privilegi di root:
"sudo docker exec -it --user root mysql-workbench bash"

dopo cambiare i permessi alla cartella .mysql passandoli a gruppo e permessi "developer"
"chown -R developer:developer .mysql"