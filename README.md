# github-cronjobs

This repository automatically triggers jobs without needing to set up a
server running 24/7. It uses Github Actions to schedule and run the jobs.

Currently, it only runs a job to update git [systemd] OBS package to the latest version. For more information, have a look at the [workflow].

[systemd]: https://build.opensuse.org/package/show/home:dspinella:systemd/systemd
[workflow]: https://github.com/danyspin97/github-cronjobs/blob/main/.github/workflows/update-systemd.yml

## License

This repository is licensed under the GPL3+ license.
