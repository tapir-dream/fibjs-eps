# os

module

## method

|       API         |       Node.js v7       |                   fibjs                       |
|-------------------|------------------------|-----------------------------------------------|
| arch              | os.arch()              | String arch()                                 |
| cpus              | os.cpus()              | Array cpus()                                  |
| endianness        | os.endianness()        | String endianness()                           |
| dateAdd           |                        | Date dateAdd(Date d,Integer num,String part)  |
| freemem           | os.freemem()           | Long freemem()                                |
| homedir           | os.homedir()           | String homedir()                              |
| hostname          | os.hostname()          | String hostname()                             |
| loadavg           | os.loadavg()           | Array loadavg()                               |
| networkInterfaces | os.networkInterfaces() | Object networkInterfaces()                    |
| memoryUsage       |                        | Object memoryUsage()                          |
| openPrinter       |                        | BufferedStream openPrinter(String name) async |
| platform          | os.platform()          | String platform()                             |
| release           | os.release()           | String release()                              |
| printerInfo       |                        | Array printerInfo()                           |
| tmpdir            | os.tmpdir()            | String tmpdir()                               |
| totalmem          | os.totalmem()          | Long totalmem()                               |
| type              | os.type()              | String type()                                 |
| userInfo          | os.userInfo([options]) | Object userInfo(Object options = {})          |
| time              |                        | Date time(String tmString="")                 |
| uptime            | os.uptime()            | Number uptime()                               |

## property

| property | Node.js v7 |            fibjs            |
|----------|------------|-----------------------------|
|Service   |            | Service                     |
|timezone  |            | readonly Integer timezone   |
|execPath  |            | readonly String execPath    |
|EOL       | EOL        | readonly String EOL         |
|constants | constants  |                             |

`Node.js os.constants`

- UV_UDP_REUSEADDR: 4
- errno:
  - E2BIG: 7
  - EACCES: 13
  - EADDRINUSE: 48
  - EADDRNOTAVAIL: 49
  - EAFNOSUPPORT: 47
  - EAGAIN: 35
  - EALREADY: 37
  - EBADF: 9
  - EBADMSG: 94
  - EBUSY: 16
  - ECANCELED: 89
  - ECHILD: 10
  - ECONNABORTED: 53
  - ECONNREFUSED: 61
  - ECONNRESET: 54
  - EDEADLK: 11
  - EDESTADDRREQ: 39
  - EDOM: 33
  - EDQUOT: 69
  - EEXIST: 17
  - EFAULT: 14
  - EFBIG: 27
  - EHOSTUNREACH: 65
  - EIDRM: 90
  - EILSEQ: 92
  - EINPROGRESS: 36
  - EINTR: 4
  - EINVAL: 22
  - EIO: 5
  - EISCONN: 56
  - EISDIR: 21
  - ELOOP: 62
  - EMFILE: 24
  - EMLINK: 31
  - EMSGSIZE: 40
  - EMULTIHOP: 95
  - ENAMETOOLONG: 63
  - ENETDOWN: 50
  - ENETRESET: 52
  - ENETUNREACH: 51
  - ENFILE: 23
  - ENOBUFS: 55
  - ENODATA: 96
  - ENODEV: 19
  - ENOENT: 2
  - ENOEXEC: 8
  - ENOLCK: 77
  - ENOLINK: 97
  - ENOMEM: 12
  - ENOMSG: 91
  - ENOPROTOOPT: 42
  - ENOSPC: 28
  - ENOSR: 98
  - ENOSTR: 99
  - ENOSYS: 78
  - ENOTCONN: 57
  - ENOTDIR: 20
  - ENOTEMPTY: 66
  - ENOTSOCK: 38
  - ENOTSUP: 45
  - ENOTTY: 25
  - ENXIO: 6
  - EOPNOTSUPP: 102
  - EOVERFLOW: 84
  - EPERM: 1
  - EPIPE: 32
  - EPROTO: 100
  - EPROTONOSUPPORT: 43
  - EPROTOTYPE: 41
  - ERANGE: 34
  - EROFS: 30
  - ESPIPE: 29
  - ESRCH: 3
  - ESTALE: 70
  - ETIME: 101
  - ETIMEDOUT: 60
  - ETXTBSY: 26
  - EWOULDBLOCK: 35
  - EXDEV: 18
- signals
  - SIGHUP: 1
  - SIGINT: 2
  - SIGQUIT: 3
  - SIGILL: 4
  - SIGTRAP: 5
  - SIGABRT: 6
  - SIGIOT: 6
  - SIGBUS: 10
  - SIGFPE: 8
  - SIGKILL: 9
  - SIGUSR1: 30
  - SIGSEGV: 11
  - SIGUSR2: 31
  - SIGPIPE: 13
  - SIGALRM: 14
  - SIGTERM: 15
  - SIGCHLD: 20
  - SIGCONT: 19
  - SIGSTOP: 17
  - SIGTSTP: 18
  - SIGTTIN: 21
  - SIGTTOU: 22
  - SIGURG: 16
  - SIGXCPU: 24
  - SIGXFSZ: 25
  - SIGVTALRM: 26
  - SIGPROF: 27
  - SIGWINCH: 28
  - SIGIO: 23
  - SIGINFO: 29
  - SIGSYS: 12 