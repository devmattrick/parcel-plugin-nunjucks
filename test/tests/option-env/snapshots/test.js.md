# Snapshot report for `test/tests/option-env/test.js`

The actual snapshot is saved in `test.js.snap`.

Generated by [AVA](https://avajs.dev).

## option-env

> option-env

    {
      $bundleId: 1,
      $type: 'Bundle',
      assets: [
        {
          $assetId: 1,
          $type: 'AssetRef',
        },
      ],
      childBundles: [],
      entryAsset: {
        $ancestors: [
          'NunjucksAsset',
          'HTMLAsset',
          'Asset',
          'Object',
        ],
        $assetId: 1,
        $type: 'Asset',
        basename: 'index.html.njk',
        dependencies: {
          'test/tests/option-env/nunjucks.config.js': {
            includedInParent: true,
            name: 'test/tests/option-env/nunjucks.config.js',
          },
        },
        entryFiles: [
          'index.html.njk',
        ],
        generated: {
          html: `<!DOCTYPE html>␊
          <html>␊
              <head>␊
                  <meta charset="UTF-8">␊
                  <title>Custom Nunjucks instance (config.env)</title>␊
              </head>␊
              <body>␊
                  <span>Hello, success: <span>WORLD</span>!</span>␊
              </body>␊
          </html>␊
          `,
        },
        name: 'index.html.njk',
        rootDir: 'test/tests/option-env',
        type: 'html',
      },
      name: 'dist/index.html.html',
      siblingBundles: [],
      type: 'html',
    }
