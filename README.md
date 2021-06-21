# Exim

**Exim** is a message transfer agent (MTA) developed at the University of Cambridge for use on Unix systems connected to the Internet. It is freely available under the terms of the GNU General Public Licence. In style it is similar to Smail 3, but its facilities are more general. There is a great deal of flexibility in the way mail can be routed, and there are extensive facilities for checking incoming mail. Exim can be installed in place of sendmail, although the configuration of exim is quite different to that of sendmail.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/exim
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y exim
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/exim).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/exim) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
