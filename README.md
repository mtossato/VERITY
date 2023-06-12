# VERITY
MicroServiços de Lançamento
# Documentos
# EF_0001 - Lancamento Debito x Credito.pdf - Documento ref. ao Projeto
# script_SQL.sql - Script de banco e tabela
# web.rar - pasta compactada web onde consta todos os arquivos necessários para o sistema 

# ////////////////////////////////////////////////////////////////////
# Demonstração de Micro Servicos ( Lançamento e Relatório )
# Desenvolvido em Genexus (C#) e Sql Server com arquitetura SOA
# Mesmo sendo uma arquitetura antiga para visualização acredito que é o mais facil, mas por exemplo poderia ser feito por REST (API) onde é a mesma arquitetura de desenvolvimento.
# Normalmente Documentos especificos para Desenho da Solução, Especificação Funcional e Especificação Técnica e Documento de Testes porem por se tratar de uma "solução" simples gerei 1 documento com todas as informações EF_0001 - Lancamento Debito x Credito.pdf

# Banco de Dados SQL 
# Banco nome GXLAN
# Usuário Lancamento e senha 123
# Script criação do banco / Tabela ScriptSQL.sql  ( Atenção para os arquivos MDfs e LDFs )
# Criação do Banco e Tabela LCT0001 
#--------------------------------------------------------------------------------------------------
# Descompactar WEB.rar para a pasta WEB e criar um site ou um Pasta Virtual no IIS apontado para a pasta WEB com Pool 4.0 Integrado
# Alterar seguintes dados em WEB\web.config
#     
#    Colocar abaixo o caminho do banco SQL
#    <add key="Connection-Default-Datasource" value="uocMBWp+lEvwHmWFybJL8QDlG23vz27vPV7w0z1tU/V=" />
#     Usuário - Utilizado lancamento
#    <add key="Connection-Default-User" value="yYZ8W4ZVrp6a4QSE1afFz6==" />
#    Senha - Utilizado 123
#    <add key="Connection-Default-Password" value="MDYrmraAJmSvQA/35HOeHX==" />
#    Nome do Banco
#    <add key="Connection-Default-DB" value="GXLAN" />
#     Schema - Padrão dbo
#    <add key="Connection-Default-Schema" value="82sPNmMP8O3TlpdEZk1r8E==" />



