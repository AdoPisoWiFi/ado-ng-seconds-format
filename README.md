# Seconds Format

Angularjs module that provides `adotime` filter. It displays remainig time of customers in a human-readable format.

- Module name: `ado.seconds-format`
- Filter: `adotime`

### Usage

```javascript
<span>{{user.remaining_time | adotime:'short'}}</span>

or

// default long
<span>{{user.remaining_time | adotime:'long'}}</span>

```
