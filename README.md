# Memory eater
1. Create a file of size 130MB on a test host
   ```
   # yes this is test file | head -c 130M > /tmp/test.file
   ```
2. Run the playbook (change `filepath`)
