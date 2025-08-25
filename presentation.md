## Retour de méthode
Renvoyer un Optional\<T> plutôt qu’un T permet d’indiquer au développeur qui utilisera la méthode que que la vavelur de retour peut être vide.

Par contre, on revoie T si la valeur de retour est forcément une valeur non nulle.
```
Optional<Venue> optVenue = findVenueById(12L);
```
