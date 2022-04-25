## API Report File for "@eppo/node-server-sdk"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public
export interface IClientConfig {
    apiKey: string;
}

// @public
export interface IEppoClient {
    getAssignment(subject: string, flag: string): string;
}

// @public
export function init(config: IClientConfig): IEppoClient;

// (No @packageDocumentation comment for this package)

```