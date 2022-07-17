# DenoSpaceXData

This project parses data for SpaceX Rocket Launchs from the [SpaceXAPI][SpaceXAPI] using
[Deno][deno] and [Lodash][lodash].


## Dependencies

- [Git][]
- [Deno][]

## Build instructions

```sh
# Clone this repo
git clone https://github.com/dmarcr1997/UdacityCPPCapstone.git
cd	DenoSpaceXData
# Build/Run
deno run --allow-net=https://api.spacexdata.com/v3/launches --allow-write mod.ts
```

## License

Author: Damon M. Rocha

This project is distributed under the terms of the MIT license
[&lt;LICENSE&gt;](LICENSE).



[Deno]: https://deno.land/
[Lodash]: https://deno.land/x/lodash@4.17.15-npm
[Git]: https://git-scm.com
[SpaceXAPI]: https://api.spacexdata.com/v3/launches