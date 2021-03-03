# ddrive-network-heuristics
Networking heuristics for announcing dDrives on dSwarm

These heuristics are used in the [`@ddrive/daemon-client`](https://github.com/dwebprotocol/ddrive-daemon-client) and [`@dhub/ddrive`](https://github.com/dwebprotocol/ddrive-service).

### Usage
There's only one exported method, which is used to enable the networking heuristics:

#### `applyHeuristics(drive, networker)`

Applies networking heuristics to a drive.

- `drive`: A DDrive instance
- `networker`: A `@basestore/networker` or dHub `RemoteNetworker`

### License
MIT
