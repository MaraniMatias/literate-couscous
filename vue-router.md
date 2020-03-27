<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [vue-router](./vue-router.md)

## vue-router package

## Functions

|  Function | Description |
|  --- | --- |
|  [createMemoryHistory(base)](./vue-router.creatememoryhistory.md) | Creates a in-memory based history. The main purpose of this history is to handle SSR. It starts in a special location that is nowhere. It's up to the user to replace that location with the starter location. |
|  [createRouter({ history, routes, scrollBehavior, parseQuery, stringifyQuery, })](./vue-router.createrouter.md) |  |
|  [createWebHashHistory(base)](./vue-router.createwebhashhistory.md) |  |
|  [createWebHistory(base)](./vue-router.createwebhistory.md) |  |
|  [onBeforeRouteLeave(leaveGuard)](./vue-router.onbeforerouteleave.md) |  |
|  [parseQuery(search)](./vue-router.parsequery.md) | Transforms a queryString into a [LocationQuery](./vue-router.locationquery.md) object. Accept both, a version with the leading <code>?</code> and without Should work as URLSearchParams |
|  [stringifyQuery(query)](./vue-router.stringifyquery.md) | Stringifies a [LocationQueryRaw](./vue-router.locationqueryraw.md) object. Like <code>URLSearchParams</code>, it doesn't prepend a <code>?</code> |
|  [useLink(props)](./vue-router.uselink.md) |  |
|  [useRoute()](./vue-router.useroute.md) |  |
|  [useRouter()](./vue-router.userouter.md) |  |
|  [useView(options)](./vue-router.useview.md) |  |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [NavigationGuard](./vue-router.navigationguard.md) |  |
|  [PostNavigationGuard](./vue-router.postnavigationguard.md) |  |
|  [RouteLocationNormalized](./vue-router.routelocationnormalized.md) |  |
|  [RouteLocationNormalizedResolved](./vue-router.routelocationnormalizedresolved.md) |  |
|  [RouteLocationOptions](./vue-router.routelocationoptions.md) |  |
|  [Router](./vue-router.router.md) |  |
|  [RouteRecordNormalized](./vue-router.routerecordnormalized.md) |  |
|  [RouterHistory](./vue-router.routerhistory.md) |  |
|  [RouterOptions](./vue-router.routeroptions.md) |  |

## Variables

|  Variable | Description |
|  --- | --- |
|  [Link](./vue-router.link.md) |  |
|  [START\_LOCATION](./vue-router.start_location.md) |  |
|  [View](./vue-router.view.md) |  |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [LocationQuery](./vue-router.locationquery.md) | Normalized query object that appears in [RouteLocationNormalized](./vue-router.routelocationnormalized.md) |
|  [LocationQueryRaw](./vue-router.locationqueryraw.md) | Loose [LocationQuery](./vue-router.locationquery.md) object that can be passed to functions like [Router.push()](./vue-router.router.push.md) and [Router.replace()](./vue-router.router.replace.md) or anywhere when creating a  |
|  [RouteParams](./vue-router.routeparams.md) |  |
|  [RouteRecord](./vue-router.routerecord.md) |  |
