# cobra getting started

## Code generation

Looking at [Linode](https://www.linode.com/docs/development/go/using-cobra/)

```bash
mkdir three
cobra init --pkg-name github.com/NissesSenap/100daysofcode/three
cobra add insert
cobra add delete
cobra add list
cobra add count
```

### Generate sub-command

deleteCmd can be found in the delete.go folder.

```cobra add all -p 'deleteCmd'```

## Usage

### Alias

Will call on delete

go run main.go rm

### Global flag/input verification

go run main.go count 10 --developer "Something something"

Also notice the int is defined in count.go
