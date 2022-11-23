## API Report File for "@backstage/plugin-airbrake-backend"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { Config } from '@backstage/config';
import express from 'express';
import { Logger } from 'winston';

// @public
export interface AirbrakeConfig {
  apiKey: string;
}

// @public
export function createRouter(options: RouterOptions): Promise<express.Router>;

// @public
export function extractAirbrakeConfig(config: Config): AirbrakeConfig;

// @public
export interface RouterOptions {
  airbrakeConfig: AirbrakeConfig;
  logger: Logger;
}
```