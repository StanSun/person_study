# proxy

本地开启shadowsocks后

```shell
export http_proxy=http://127.0.0.1:1087;export https_proxy=http://127.0.0.1:1087;

➜  etcd git:(master) ✗ go get -u github.com/etcd-io/etcd
go: finding github.com/etcd-io/etcd v3.3.12+incompatible
go: downloading github.com/etcd-io/etcd v3.3.12+incompatible
go: extracting github.com/etcd-io/etcd v3.3.12+incompatible
go: finding github.com/coreos/etcd/etcdmain latest
go: finding github.com/coreos/etcd v3.3.12+incompatible
go: downloading github.com/coreos/etcd v3.3.12+incompatible
go: extracting github.com/coreos/etcd v3.3.12+incompatible
go: downloading google.golang.org/grpc v1.14.0
go: downloading github.com/ghodss/yaml v1.0.1-0.20190212211648-25d852aebe32
go: downloading github.com/prometheus/client_golang v0.8.0
go: downloading github.com/coreos/go-semver v0.2.0
go: downloading github.com/spf13/cobra v0.0.3
go: downloading golang.org/x/net v0.0.0-20180906233101-161cd47e91fd
go: extracting github.com/ghodss/yaml v1.0.1-0.20190212211648-25d852aebe32
go: downloading github.com/gogo/protobuf v1.0.0
go: extracting github.com/coreos/go-semver v0.2.0
go: downloading gopkg.in/yaml.v2 v2.2.2
go: extracting github.com/prometheus/client_golang v0.8.0
go: extracting github.com/spf13/cobra v0.0.3
go: downloading github.com/tmc/grpc-websocket-proxy v0.0.0-20170815181823-89b8d40f7ca8
go: extracting github.com/tmc/grpc-websocket-proxy v0.0.0-20170815181823-89b8d40f7ca8
go: downloading github.com/prometheus/common v0.0.0-20180518154759-7600349dcfe1
go: extracting github.com/prometheus/common v0.0.0-20180518154759-7600349dcfe1
go: downloading github.com/prometheus/procfs v0.0.0-20180612222113-7d6f385de8be
go: extracting github.com/prometheus/procfs v0.0.0-20180612222113-7d6f385de8be
go: downloading go.uber.org/zap v1.9.1
go: extracting github.com/gogo/protobuf v1.0.0
go: extracting gopkg.in/yaml.v2 v2.2.2
go: downloading github.com/grpc-ecosystem/grpc-gateway v1.4.1
go: downloading github.com/coreos/pkg v0.0.0-20160727233714-3ac0863d7acf
go: extracting github.com/coreos/pkg v0.0.0-20160727233714-3ac0863d7acf
go: extracting google.golang.org/grpc v1.14.0
go: extracting github.com/grpc-ecosystem/grpc-gateway v1.4.1
go: downloading github.com/golang/protobuf v1.2.0
go: downloading github.com/coreos/go-systemd v0.0.0-20180511133405-39ca1b05acc7
go: downloading github.com/sirupsen/logrus v1.0.5
go: downloading github.com/spf13/pflag v1.0.1
go: downloading github.com/jonboulle/clockwork v0.1.0
go: downloading github.com/grpc-ecosystem/go-grpc-middleware v1.0.1-0.20190118093823-f849b5445de4
go: extracting github.com/jonboulle/clockwork v0.1.0
go: extracting github.com/sirupsen/logrus v1.0.5
go: downloading github.com/soheilhy/cmux v0.1.4
go: extracting github.com/spf13/pflag v1.0.1
go: extracting github.com/grpc-ecosystem/go-grpc-middleware v1.0.1-0.20190118093823-f849b5445de4
go: extracting go.uber.org/zap v1.9.1
go: extracting github.com/coreos/go-systemd v0.0.0-20180511133405-39ca1b05acc7
go: extracting github.com/soheilhy/cmux v0.1.4
go: extracting golang.org/x/net v0.0.0-20180906233101-161cd47e91fd
go: downloading github.com/beorn7/perks v0.0.0-20180321164747-3a771d992973
go: downloading github.com/gorilla/websocket v0.0.0-20170926233335-4201258b820c
go: extracting github.com/golang/protobuf v1.2.0
go: downloading github.com/xiang90/probing v0.0.0-20190116061207-43a291ad63a2
go: extracting github.com/beorn7/perks v0.0.0-20180321164747-3a771d992973
go: downloading golang.org/x/crypto v0.0.0-20180608092829-8ac0e0d97ce4
go: extracting github.com/xiang90/probing v0.0.0-20190116061207-43a291ad63a2
go: extracting github.com/gorilla/websocket v0.0.0-20170926233335-4201258b820c
go: downloading google.golang.org/genproto v0.0.0-20180608181217-32ee49c4dd80
go: downloading golang.org/x/sys v0.0.0-20180909124046-d0be0721c37e
go: downloading github.com/golang/groupcache v0.0.0-20160516000752-02826c3e7903
go: downloading go.uber.org/atomic v1.3.2
go: downloading github.com/prometheus/client_model v0.0.0-20170216185247-6f3806018612
go: downloading github.com/ugorji/go v1.1.2
go: extracting github.com/golang/groupcache v0.0.0-20160516000752-02826c3e7903
go: downloading github.com/grpc-ecosystem/go-grpc-prometheus v1.2.0
go: extracting github.com/prometheus/client_model v0.0.0-20170216185247-6f3806018612
go: extracting github.com/grpc-ecosystem/go-grpc-prometheus v1.2.0
go: extracting github.com/ugorji/go v1.1.2
go: downloading github.com/ugorji/go/codec v0.0.0-20190204201341-e444a5086c43
go: extracting go.uber.org/atomic v1.3.2
go: downloading golang.org/x/time v0.0.0-20180412165947-fbb02b2291d2
go: downloading go.uber.org/multierr v1.1.0
go: downloading github.com/matttproud/golang_protobuf_extensions v1.0.0
go: downloading github.com/dgrijalva/jwt-go v3.2.0+incompatible
go: extracting github.com/matttproud/golang_protobuf_extensions v1.0.0
go: downloading golang.org/x/text v0.3.0
go: extracting github.com/dgrijalva/jwt-go v3.2.0+incompatible
go: extracting github.com/ugorji/go/codec v0.0.0-20190204201341-e444a5086c43
go: extracting golang.org/x/time v0.0.0-20180412165947-fbb02b2291d2
go: extracting go.uber.org/multierr v1.1.0
go: downloading github.com/google/btree v0.0.0-20180124185431-e89373fe6b4a
go: extracting github.com/google/btree v0.0.0-20180124185431-e89373fe6b4a
go: extracting golang.org/x/crypto v0.0.0-20180608092829-8ac0e0d97ce4
go: extracting golang.org/x/sys v0.0.0-20180909124046-d0be0721c37e
go: finding github.com/coreos/bbolt v1.3.2
go: extracting google.golang.org/genproto v0.0.0-20180608181217-32ee49c4dd80
go: downloading github.com/coreos/bbolt v1.3.2
go: extracting github.com/coreos/bbolt v1.3.2
go: extracting golang.org/x/text v0.3.0
➜  etcd git:(master) ✗ 

```

