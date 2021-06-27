AMQP Folder is a virtua Enviroment to run AMQP

Tutorial 1

python send.py

python receive.py

Tutorial 2

Before doing this change queue name in new task

python new_task.py "First....."

python new_task.py "Second....."

python new_task.py "Third....."

python new_task.py "Fourth....."

python new_task.py "Fifth....."

Before doing this change queue name in worker

python worker.py

python worker.py

Tutorial 3

python receive_logs.py

python receive_logs1.py

python emit_log.py "info: This is the log message"

Tutorial 4

python receive_logs_direct.py info

python emit_log_direct.py info "The message"

Tutoroial 5

python receive_logs_topic.py "*.rabbit"

python emit_log_topic.py red.rabbit Hello

