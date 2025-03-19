web: bin/sample-sleeper

worker: while true; do count=$((${COUNT:-0} + 1)); echo "$count"; bin/sample-sleeper &; sleep 1; COUNT=$count; done
