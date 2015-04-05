Ex Libris
=========

A collaborative library inventory tool.


Usage
-----

### Local

```bash
rackup -p 3000 # see http://localhost:3000
```

### Heroku

Click the button below to automatically set up Ex Libris in an app running on your Heroku account.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Alternatively, you can manually create a Heroku app and use Git to push and deploy.


Development
-----------

This application deployment is automated through an [`app.json`][app-json-intro] file (see [deploying to heroku][doc-heroku]). The validity of that file is verified as part of the default test suite (`rake`) using the [app.json validator][app-json-validator] provided by the Heroku developers. Run `rake app_json:validate` for help.

  [app-json-intro]: https://blog.heroku.com/archives/2014/5/22/introducing_the_app_json_application_manifest
  [app-json-validator]: https://github.com/app-json/app.json
  [doc-heroku]: https://github.com/gonzalo-bulnes/ex_libris/blob/master/README.md#heroku


License
-------

    Ex Libris is a collaborative library inventory tool.

    Copyright (C) 2015  Gonzalo Bulnes Guilpain

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
