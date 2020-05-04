 # Счётчики INSTRUCTION, BRANCH и LINE.
 
 ## Счётчик INSTRUCTION.
 **Счётчик INSTRUCTION** предоставляет информацию о количестве кода, который был выполнен или пропущен. Этот показатель полностью независим от исходного форматирования и всегда доступен, даже при отсутствии отладочной информации в файлах классов.
 
 ## Счётчик BRANCH.
**Счётчик BRANCH** для всех операторов if и switch. Эта метрика подсчитывает общее количество таких ветвей в методе и определяет количество выполненных или пропущенных веток. Покрытие веток всегда доступно, даже в отсутствие отладочной информации в файлах классов. 
*Обратите внимание, что обработка исключений не рассматривается как ветви в контексте этого определения счетчика.*

## Счётчик LINE.
**Счётчик LINE** рассчитывает информацию покрытия для отдельных строк во всех файлах классов, которые были скомпилированы с отладочной информацией. Строка источника считается выполненной, когда выполнена хотя бы одна инструкция, назначенная этой строке.
