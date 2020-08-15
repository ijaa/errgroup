# errgroup
- golang.org/x/sync/errgroup with panic recover
- when the errgroup.Go called func f has panic inner, it will write the panic stack trace to os.Stderr and return an error with panic info
