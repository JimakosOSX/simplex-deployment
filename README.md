# Ansible role to set-up a SimpleXChat server instance

[Official Doc used](https://github.com/simplex-chat/simplex-chat/blob/stable/docs/SERVER.md)

## Instructions

Copy `defaults/main.yml.example` to `defaults/main.yml` to use your own options.


Fill `inventory` with the desired server. Modify `test.yml` according to your setup.

Install role dependencies `ansible-galaxy install -r roles/requirements.yml`

Run `test.yml`.

 
## TODO
- Add WebRTC
