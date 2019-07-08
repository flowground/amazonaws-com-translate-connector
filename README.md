# ![LOGO](logo.png) Amazon Translate **flow**ground Connector

## Description

A generated **flow**ground connector for the Amazon Translate API (version 2017-07-01).

Generated from: https://api.apis.guru/v2/specs/amazonaws.com/translate/2017-07-01/swagger.json<br/>
Generated at: 2019-07-08T14:35:49+03:00

## API Description

Provides translation between one source language and another of the same set of languages.<br/>

## Authorization

Supported authorization schemes:
- API Key
## Actions

### DeleteTerminology
> A synchronous action that deletes a custom terminology.<br/>

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### GetTerminology
> Retrieves a custom terminology.<br/>

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### ImportTerminology
<blockquote><p>Creates or updates a custom terminology, depending on whether or not one already exists for the given terminology name. Importing a terminology with the same name as an existing one will merge the terminologies based on the chosen merge strategy. Currently, the only supported merge strategy is OVERWRITE, and so the imported terminology will overwrite an existing terminology of the same name.</p> <p>If you import a terminology that overwrites an existing one, the new terminology take up to 10 minutes to fully propagate and be available for use in a translation due to cache policies with the DataPlane service that performs the translations.</p></blockquote>

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### ListTerminologies
> Provides a list of custom terminologies associated with your account.<br/>

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### TranslateText
<blockquote><p>Translates input text from the source language to the target language. It is not necessary to use English (en) as either the source or the target language but not all language combinations are supported by Amazon Translate. For more information, see <a href="http://docs.aws.amazon.com/translate/latest/dg/pairs.html">Supported Language Pairs</a>.</p> <ul> <li> <p>Arabic (ar)</p> </li> <li> <p>Chinese (Simplified) (zh)</p> </li> <li> <p>Chinese (Traditional) (zh-TW)</p> </li> <li> <p>Czech (cs)</p> </li> <li> <p>Danish (da)</p> </li> <li> <p>Dutch (nl)</p> </li> <li> <p>English (en)</p> </li> <li> <p>Finnish (fi)</p> </li> <li> <p>French (fr)</p> </li> <li> <p>German (de)</p> </li> <li> <p>Hebrew (he)</p> </li> <li> <p>Indonesian (id)</p> </li> <li> <p>Italian (it)</p> </li> <li> <p>Japanese (ja)</p> </li> <li> <p>Korean (ko)</p> </li> <li> <p>Polish (pl)</p> </li> <li> <p>Portuguese (pt)</p> </li> <li> <p>Russian (ru)</p> </li> <li> <p>Spanish (es)</p> </li> <li> <p>Swedish (sv)</p> </li> <li> <p>Turkish (tr)</p> </li> </ul> <p>To have Amazon Translate determine the source language of your text, you can specify <code>auto</code> in the <code>SourceLanguageCode</code> field. If you specify <code>auto</code>, Amazon Translate will call Amazon Comprehend to determine the source language.</p></blockquote>

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

## License

**flow**ground :- Telekom iPaaS / amazonaws-com-translate-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
