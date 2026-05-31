<div align="center">

> *"Talk is cheap, show me the code."* — Linus Torvalds

</div>

<br>

<table align="center">
<tr>
<td valign="top" width="50%">

```go
package main

import "fmt"

type Dev struct {
    Name string
    OS   string
    Mood string
}

func (d Dev) greet() string {
    return fmt.Sprintf("hey, i'm %s", d.Name)
}

func main() {
    me := Dev{
        Name: "seoz",
        OS:   "Linux",
        Mood: "always_shipping",
    }
    fmt.Println(me.greet())
}
```

</td>
<td valign="top" width="50%">

```sh
$ whoami
seoz

$ uname -sr
Linux 7.0.10-arch1-1

$ uptime -p
up 14 hours, 32 minutes

$ echo $MOOD
always_shipping

$ echo $LANGS
go python html

$ chmod +x ~/scripts/RemoveWindows.sh

$ ./home/seoz/scripts/RemoveWindows.sh
Operation complete, Windows partition was successfully nuked.
```

</td>
</tr>
</table>

<br>

<p align="center">
  <a href="">
    <img src="https://skillicons.dev/icons?i=go,python,html,linux,arch,bash" alt="Skills Icons" />
  </a>
</p>
