# couchedev
Development environment for CouchDB

## Install

Clone this project, and `cd` into it.  Then use Vagrant to boot up the virtual machine.

```sh
$ vagrant up
```

The VM will publish on port `5984` to see couchDB.  To check that your DB is running:

``` sh
$ curl http://localhost:5984
```
You shou see a similar response to this.

```sh
{
  "couchdb": "Welcome",
  "uuid": "90e9c243e0f3d5297e2c8854cbdc83dd",
  "version": "1.5.0",
  "vendor": {
    "name": "Ubuntu",
    "version": "14.04"
  }
}
```

### Admin portal

To view the admin portal, navigate to `http://127.0.0.1:5984/_utils/`

## Resources

* http://guide.couchdb.org/draft/tour.html
