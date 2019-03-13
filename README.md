## INSTALL

npm i @fortawesome/angular-fontawesome

npm i @fortawesome/fontawesome-svg-core

npm i @fortawesome/free-solid-svg-icons

npm i @fortawesome/free-regular-svg-icons


## IMPORTS 
```
> app.module.ts

import { FontAwesomeModule } from '@fortawesome/angular-fontawesome';
import { fas } from '@fortawesome/free-solid-svg-icons'
import { far } from '@fortawesome/free-regular-svg-icons'
import { fab } from '@fortawesome/free-brands-svg-icons'
import { library } from '@fortawesome/fontawesome-svg-core'

library.add(fas,far,fab)// add all icons

@NgModule({
    ...

imports:[
    ...
    FontAwesomeModule
]
```


> page.module.ts

```
import { FontAwesomeModule } from '@fortawesome/angular-fontawesome';
imports:[
    ...
    FontAwesomeModule
] 
```

## LINKS
Angular-fontawesome
https://github.com/FortAwesome/angular-fontawesome

Gallery fontawesome
https://fontawesome.com/icons?d=gallery
