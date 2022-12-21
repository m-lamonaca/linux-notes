# Process Exit Codes

When a process terminates it returns an **exit code** (an integer number) to indicate whether the operation was successful or not.  
Generally an exit code of `0` (zero) indicates success while any other integer means some kind of faliure.

```sh
echo $?  # output last exit code
```

## Special Exit Codes

- `127`: command not found (bash)
- `137`: process was killed (128 + n, n signal number)
