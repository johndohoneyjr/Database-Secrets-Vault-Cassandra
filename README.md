# Hashicorp Vault Dynamic Secrets using Cassandra

This file contains 2 directories:

docs -- The instructions to install Java and Datastax Cassandra Community Edition on your Mac, along with the script of the demo using Cassandra

conf -- changes I needed to make to:
        1. Make cassandra work with Vault (cassandra.yaml)
        2. JVM options that were commented out to run with Java 10/11
        
Don't forget, create a <cassandra root>/logs directory, otherwise, Cassandra will not start.

Enjoy Database Secrets with Vault
