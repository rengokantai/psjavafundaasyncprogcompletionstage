# psjavafundaasyncprogcompletionstage

## 2. Introducing Asynchronous vs. Concurrent Tasks
### 6 Using the executor pattern
```
ExecutorService service = Executors.newSingleThreadExecutorService();
Runnable task = ()->{}
Future future = service.submit(task);
```
