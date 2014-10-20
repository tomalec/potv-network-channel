# &lt;potv-network-channel&gt;

> Polymer Custom Element representing network channel (incoming/outgoing packages) in Puppet Operational Transformation communication Visualization

## Demo

[Check it live!](http://tomalec.github.io/potv-network-channel)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install potv-network-channel --save
```

Or [download as ZIP](https://github.com/tomalec/potv-network-channel/archive/gh-pages.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/potv-network-channel/src/potv-network-channel.html">
    ```

3. Start using it!

    ```html
    <potv-network-channel></potv-network-channel>
    ```

## Options

Attribute     | Options            | Default      | Description
---           | ---                | ---          | ---
`direction`   | `"up"` \| `"down"` | `down`       | Direction of packages flow

## Methods

Method        | Parameters                           | Returns              | Description
---           | ---                                  | ---                  | ---
`transfer()`  |   *{String}* **index** (_default_ 0) | "Transfered" Element | Transfers child element of given index.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/tomalec/potv-network-channel/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
