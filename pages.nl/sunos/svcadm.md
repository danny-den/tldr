# svcadm

> Manipuleer service instanties.
> Meer informatie: <https://www.unix.com/man-page/linux/1m/svcadm>.

- Inschakelen van een service in de service database:

`svcadm enable {{service_naam}}`

- Uitschakelen van een service in de service database:

`svcadm disable {{service_naam}}`

- Herstarten van een draaiende service:

`svcadm restart {{service_naam}}`

- Refresh de configuratie van een service:

`svcadm refresh {{service_naam}}`

- Haal een service uit maintenance state, en schakel deze in:

`svcadm clear {{service_naam}}`
