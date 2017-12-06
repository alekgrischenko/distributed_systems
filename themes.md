# Список возможных тем для курса "Распределенные системы"

## Теория

Consitency: Strong, Weak, Eventual

CAP в оригинальном виде и современных интерпретациях

Time & Order, Lamport Clock, Vector Clock

Consensus, выбор мастера, Raft

Replication, master-slave, master-master, sync, async.

Fault Tolerance, Resilience.

CRDT Convergent replicated data types

Распределенные транзакции.


## Изучение существующих систем

ZooKeeper

Cassandra

Riak


## Практика, отдельные упражнения

Можно делать на локальном компьютере.

https://en.wikipedia.org/wiki/Consistent_hashing

Consistent hashing using virtual nodes https://github.com/mixu/vnodehash

Vector clock

Реализация чего-нибудь из CRDT (PN-Counter, 2P-Set)

Raft, выбор мастера


## Практика, построение некой более-менее работающей системы

Какой-то сервис с АПИ, который можно развернуть на серверах, и натравить на него тесты.

Технологический стэк:
- JVM (Java, Scala, любой JVM язык)
- EVM (Erlang или Elixir)
- Python

Jepsen – фреймворк для тестирования распределённых систем.
https://jepsen.io/


## Источники инфы

Mikito Takada​ «Distributed systems. for fun and profit».

Data Intensive Applications. Martin Kleppmann.

Designing for Scalability with Erlang/OTP. Implementing Robust, Fault-Tolerant Systems By Francesco Cesarini, Steve Vinoski
