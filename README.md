# organizer

## code-server Setup

```sh
pkg install tur-repo
pkg install code-server
```

### Configuration

```yaml
bind-addr: 0.0.0.0:8080
auth: none
```

## git

```
git config --global user.email "keerthivarman.nageshwaran.outlook.com"
git config --global user.name "Keerthivarman Nageshwaran"
```

## Node-Red

```sh
apt install coreutils nano nodejs
npm i -g node-red
node-red
```

### Configuration

```json
        projects: {
            /** To enable the Projects feature, set this value to true */
            enabled: true,
            workflow: {
                /** Set the default projects workflow mode.
                 *  - manual - you must manually commit changes
                 *  - auto - changes are automatically committed
                 * This can be overridden per-user from the 'Git config'
                 * section of 'User Settings' within the editor
                 */
                mode: "manual"
            }
        },
```

## Termux

```sh
apt install termux-api
termux-setup-storage
```