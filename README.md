# Angular Component OnOff

[![CircleCI](https://circleci.com/gh/Nexucis/ng-onoff.svg?style=shield)](https://circleci.com/gh/Nexucis/ng-onoff)

This is an angular module that can be helped to integrate the original game https://github.com/starzonmyarmz/js13k-2018[OnOff]

## Installation

This is an angular module that can be helped to integrate the original game [OnOff](https://github.com/starzonmyarmz/js13k-2018)

```bash
npm install ng-onoff --save
```

## Usage

First import NgOnOffModule in the module where you wish to display the game (it can be another module than the AppModule)

```typescript
import { BrowserModule } from '@angular/platform-browser';
import { NgModule } from '@angular/core';

import { AppComponent } from './app.component';
import { NgOnoffModule } from 'ng-onoff/ng-onoff.module';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    NgOnoffModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

And then use the component in a container that suits you :)

```html
<div style="height: 100vh">
  <ng-onoff></ng-onoff>
</div>

```

## License

The MIT License ([MIT](./LICENSE))

Copyright (c) 2019 Augustin Husson
