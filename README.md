This project attempts to demonsrate that bundler 1.1 is ignoring source order.

Expected behavior: because the `path '.'` is specified (both first and last, to cover that issue), it should use the local foursquare 0.0.1

Actual behavior: if Bundler is allowed to go online (.e.g, not using --local), it will take the higher-version foursquare 0.3.4
