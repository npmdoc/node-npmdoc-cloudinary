# api documentation for  [cloudinary (v1.8.0)](http://cloudinary.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-cloudinary.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cloudinary) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cloudinary.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cloudinary)
#### Cloudinary NPM for node.js integration

[![NPM](https://nodei.co/npm/cloudinary.png?downloads=true)](https://www.npmjs.com/package/cloudinary)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cloudinary/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-cloudinary_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cloudinary/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cloudinary/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cloudinary/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cloudinary",
        "email": "info@cloudinary.com"
    },
    "browserify": {
        "transform": [
            "coffeeify"
        ]
    },
    "bugs": {
        "url": "https://github.com/cloudinary/cloudinary_npm/issues"
    },
    "dependencies": {
        "lodash": "3.10.x",
        "q": "1.4.x"
    },
    "description": "Cloudinary NPM for node.js integration",
    "devDependencies": {
        "coffee-script": "^1.10.0",
        "dotenv": "1.x",
        "expect.js": "0.3.x",
        "jsdom": "^9.5.0",
        "jsdom-global": "^2.1.0",
        "mocha": "2.3.x",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "52e7a18dfe3c0ece01abc71341be95d0ea198d85",
        "tarball": "https://registry.npmjs.org/cloudinary/-/cloudinary-1.8.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "6896efff8d5ed5c0e085d47aa637c9b77d5a373b",
    "homepage": "http://cloudinary.com",
    "license": "MIT",
    "main": "cloudinary.js",
    "maintainers": [
        {
            "name": "cloudinary",
            "email": "info@cloudinary.com"
        }
    ],
    "name": "cloudinary",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cloudinary/cloudinary_npm.git"
    },
    "scripts": {
        "compile": "coffee --map -o lib -c src",
        "prepublish": "npm run compile",
        "pretest": "npm run compile",
        "test": "mocha -R spec --recursive test/",
        "watch": "coffee --watch --map -o lib -c src"
    },
    "version": "1.8.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cloudinary](#apidoc.module.cloudinary)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>PreloadedFile (file_info)](#apidoc.element.cloudinary.PreloadedFile)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>cloudinary_js_config ()](#apidoc.element.cloudinary.cloudinary_js_config)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>config (new_config, new_value)](#apidoc.element.cloudinary.config)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>image (source, options)](#apidoc.element.cloudinary.image)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>upload_stream (options)](#apidoc.element.cloudinary.upload_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>url (public_id, options)](#apidoc.element.cloudinary.url)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>video (public_id, options)](#apidoc.element.cloudinary.video)
1.  object <span class="apidocSignatureSpan">cloudinary.</span>PreloadedFile.prototype
1.  object <span class="apidocSignatureSpan">cloudinary.</span>akamai
1.  object <span class="apidocSignatureSpan">cloudinary.</span>api
1.  object <span class="apidocSignatureSpan">cloudinary.</span>upload_stream.prototype
1.  object <span class="apidocSignatureSpan">cloudinary.</span>uploader
1.  object <span class="apidocSignatureSpan">cloudinary.</span>utils
1.  object <span class="apidocSignatureSpan">cloudinary.</span>v2
1.  object <span class="apidocSignatureSpan">cloudinary.</span>v2.api
1.  object <span class="apidocSignatureSpan">cloudinary.</span>v2.uploader
1.  string <span class="apidocSignatureSpan">cloudinary.</span>AKAMAI_SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.</span>BLANK
1.  string <span class="apidocSignatureSpan">cloudinary.</span>CF_SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.</span>SHARED_CDN

#### [module cloudinary.PreloadedFile](#apidoc.module.cloudinary.PreloadedFile)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>PreloadedFile (file_info)](#apidoc.element.cloudinary.PreloadedFile.PreloadedFile)

#### [module cloudinary.PreloadedFile.prototype](#apidoc.module.cloudinary.PreloadedFile.prototype)
1.  [function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>identifier ()](#apidoc.element.cloudinary.PreloadedFile.prototype.identifier)
1.  [function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>is_valid ()](#apidoc.element.cloudinary.PreloadedFile.prototype.is_valid)
1.  [function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>split_format (identifier)](#apidoc.element.cloudinary.PreloadedFile.prototype.split_format)
1.  [function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>toJSON ()](#apidoc.element.cloudinary.PreloadedFile.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>toString ()](#apidoc.element.cloudinary.PreloadedFile.prototype.toString)

#### [module cloudinary.akamai](#apidoc.module.cloudinary.akamai)
1.  [function <span class="apidocSignatureSpan">cloudinary.akamai.</span>generateAkamaiToken (options)](#apidoc.element.cloudinary.akamai.generateAkamaiToken)

#### [module cloudinary.api](#apidoc.module.cloudinary.api)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>create_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.create_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>create_transformation (name, definition, callback, options)](#apidoc.element.cloudinary.api.create_transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>create_upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.create_upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>create_upload_preset (callback, options)](#apidoc.element.cloudinary.api.create_upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_all_resources (callback, options)](#apidoc.element.cloudinary.api.delete_all_resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_derived_resources (derived_resource_ids, callback, options)](#apidoc.element.cloudinary.api.delete_derived_resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_resources (public_ids, callback, options)](#apidoc.element.cloudinary.api.delete_resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_resources_by_prefix (prefix, callback, options)](#apidoc.element.cloudinary.api.delete_resources_by_prefix)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_resources_by_tag (tag, callback, options)](#apidoc.element.cloudinary.api.delete_resources_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.delete_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_transformation (transformation, callback, options)](#apidoc.element.cloudinary.api.delete_transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.delete_upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_upload_preset (name, callback, options)](#apidoc.element.cloudinary.api.delete_upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>get_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.get_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>list_streaming_profiles (callback, options)](#apidoc.element.cloudinary.api.list_streaming_profiles)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>only ()](#apidoc.element.cloudinary.api.only)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>ping (callback, options)](#apidoc.element.cloudinary.api.ping)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>publish_by_ids (public_ids, callback, options)](#apidoc.element.cloudinary.api.publish_by_ids)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>publish_by_prefix (prefix, callback, options)](#apidoc.element.cloudinary.api.publish_by_prefix)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>publish_by_tag (tag, callback, options)](#apidoc.element.cloudinary.api.publish_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>resource (public_id, callback, options)](#apidoc.element.cloudinary.api.resource)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>resource_types (callback, options)](#apidoc.element.cloudinary.api.resource_types)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>resources (callback, options)](#apidoc.element.cloudinary.api.resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_context (key, value, callback, options)](#apidoc.element.cloudinary.api.resources_by_context)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_ids (public_ids, callback, options)](#apidoc.element.cloudinary.api.resources_by_ids)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_moderation (kind, status, callback, options)](#apidoc.element.cloudinary.api.resources_by_moderation)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_tag (tag, callback, options)](#apidoc.element.cloudinary.api.resources_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>restore (public_ids, callback, options)](#apidoc.element.cloudinary.api.restore)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>root_folders (callback, options)](#apidoc.element.cloudinary.api.root_folders)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>sub_folders (path, callback, options)](#apidoc.element.cloudinary.api.sub_folders)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>tags (callback, options)](#apidoc.element.cloudinary.api.tags)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>transformation (transformation, callback, options)](#apidoc.element.cloudinary.api.transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>transformations (callback, options)](#apidoc.element.cloudinary.api.transformations)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update (public_id, callback, options)](#apidoc.element.cloudinary.api.update)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update_resources_access_mode_by_ids (access_mode, ids, callback, options)](#apidoc.element.cloudinary.api.update_resources_access_mode_by_ids)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update_resources_access_mode_by_prefix (access_mode, prefix, callback, options)](#apidoc.element.cloudinary.api.update_resources_access_mode_by_prefix)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update_resources_access_mode_by_tag (access_mode, tag, callback, options)](#apidoc.element.cloudinary.api.update_resources_access_mode_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.update_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update_transformation (transformation, updates, callback, options)](#apidoc.element.cloudinary.api.update_transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update_upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.update_upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>update_upload_preset (name, callback, options)](#apidoc.element.cloudinary.api.update_upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_mappings (callback, options)](#apidoc.element.cloudinary.api.upload_mappings)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_preset (name, callback, options)](#apidoc.element.cloudinary.api.upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_presets (callback, options)](#apidoc.element.cloudinary.api.upload_presets)
1.  [function <span class="apidocSignatureSpan">cloudinary.api.</span>usage (callback, options)](#apidoc.element.cloudinary.api.usage)

#### [module cloudinary.upload_stream](#apidoc.module.cloudinary.upload_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.</span>upload_stream (options)](#apidoc.element.cloudinary.upload_stream.upload_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.upload_stream.</span>super_ (options)](#apidoc.element.cloudinary.upload_stream.super_)

#### [module cloudinary.upload_stream.prototype](#apidoc.module.cloudinary.upload_stream.prototype)
1.  [function <span class="apidocSignatureSpan">cloudinary.upload_stream.prototype.</span>_flush (next)](#apidoc.element.cloudinary.upload_stream.prototype._flush)
1.  [function <span class="apidocSignatureSpan">cloudinary.upload_stream.prototype.</span>_transform (data, encoding, next)](#apidoc.element.cloudinary.upload_stream.prototype._transform)

#### [module cloudinary.uploader](#apidoc.module.cloudinary.uploader)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>add_context (context, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.add_context)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>add_tag (tag, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.add_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>create_archive (callback, options, target_format)](#apidoc.element.cloudinary.uploader.create_archive)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>create_zip (callback, options)](#apidoc.element.cloudinary.uploader.create_zip)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>destroy (public_id, callback, options)](#apidoc.element.cloudinary.uploader.destroy)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>direct_upload (callback_url, options)](#apidoc.element.cloudinary.uploader.direct_upload)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>explicit (public_id, callback, options)](#apidoc.element.cloudinary.uploader.explicit)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>explode (public_id, callback, options)](#apidoc.element.cloudinary.uploader.explode)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>generate_sprite (tag, callback, options)](#apidoc.element.cloudinary.uploader.generate_sprite)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>image_upload_tag (field, options)](#apidoc.element.cloudinary.uploader.image_upload_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>multi (tag, callback, options)](#apidoc.element.cloudinary.uploader.multi)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>remove_all_context (public_ids, callback, options)](#apidoc.element.cloudinary.uploader.remove_all_context)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>remove_all_tags (public_ids, callback, options)](#apidoc.element.cloudinary.uploader.remove_all_tags)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>remove_tag (tag, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.remove_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>rename (from_public_id, to_public_id, callback, options)](#apidoc.element.cloudinary.uploader.rename)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>replace_tag (tag, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.replace_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>text (text, callback, options)](#apidoc.element.cloudinary.uploader.text)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>unsigned_image_upload_tag (field, upload_preset, options)](#apidoc.element.cloudinary.uploader.unsigned_image_upload_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>unsigned_upload (file, upload_preset, callback, options)](#apidoc.element.cloudinary.uploader.unsigned_upload)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>unsigned_upload_stream (upload_preset, callback, options)](#apidoc.element.cloudinary.uploader.unsigned_upload_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload (file, callback, options)](#apidoc.element.cloudinary.uploader.upload)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_chunked (path, callback, options)](#apidoc.element.cloudinary.uploader.upload_chunked)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_chunked_stream (callback, options)](#apidoc.element.cloudinary.uploader.upload_chunked_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_large (path, callback, options)](#apidoc.element.cloudinary.uploader.upload_large)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_large_stream (_unused_, callback, options)](#apidoc.element.cloudinary.uploader.upload_large_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_stream (callback, options)](#apidoc.element.cloudinary.uploader.upload_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_tag_params (options)](#apidoc.element.cloudinary.uploader.upload_tag_params)
1.  [function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_url (options)](#apidoc.element.cloudinary.uploader.upload_url)

#### [module cloudinary.utils](#apidoc.module.cloudinary.utils)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>api_sign_request (params_to_sign, api_secret)](#apidoc.element.cloudinary.utils.api_sign_request)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>api_url (action, options)](#apidoc.element.cloudinary.utils.api_url)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>archive_params (options)](#apidoc.element.cloudinary.utils.archive_params)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>as_safe_bool (value)](#apidoc.element.cloudinary.utils.as_safe_bool)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_array (arg)](#apidoc.element.cloudinary.utils.build_array)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_custom_headers (headers)](#apidoc.element.cloudinary.utils.build_custom_headers)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_eager (transformations)](#apidoc.element.cloudinary.utils.build_eager)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_explicit_api_params (public_id, options)](#apidoc.element.cloudinary.utils.build_explicit_api_params)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_streaming_profiles_param (options)](#apidoc.element.cloudinary.utils.build_streaming_profiles_param)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_upload_params (options)](#apidoc.element.cloudinary.utils.build_upload_params)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>clear_blank (hash)](#apidoc.element.cloudinary.utils.clear_blank)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>cloudinary_js_config ()](#apidoc.element.cloudinary.utils.cloudinary_js_config)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>download_archive_url (options)](#apidoc.element.cloudinary.utils.download_archive_url)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>download_zip_url (options)](#apidoc.element.cloudinary.utils.download_zip_url)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>encode_double_array (array)](#apidoc.element.cloudinary.utils.encode_double_array)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>encode_key_value (arg)](#apidoc.element.cloudinary.utils.encode_key_value)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>generate_auth_token (options)](#apidoc.element.cloudinary.utils.generate_auth_token)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>generate_responsive_breakpoints_string (breakpoints)](#apidoc.element.cloudinary.utils.generate_responsive_breakpoints_string)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>generate_transformation_string (options)](#apidoc.element.cloudinary.utils.generate_transformation_string)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>getUserAgent ()](#apidoc.element.cloudinary.utils.getUserAgent)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>html_attrs (attrs)](#apidoc.element.cloudinary.utils.html_attrs)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>merge (hash1, hash2)](#apidoc.element.cloudinary.utils.merge)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>only ()](#apidoc.element.cloudinary.utils.only)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>option_consume (options, option_name, default_value)](#apidoc.element.cloudinary.utils.option_consume)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>present (value)](#apidoc.element.cloudinary.utils.present)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>private_download_url (public_id, format, options)](#apidoc.element.cloudinary.utils.private_download_url)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>process_request_params (params, options)](#apidoc.element.cloudinary.utils.process_request_params)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>random_public_id ()](#apidoc.element.cloudinary.utils.random_public_id)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>sign_request (params, options)](#apidoc.element.cloudinary.utils.sign_request)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>signed_preloaded_image (result)](#apidoc.element.cloudinary.utils.signed_preloaded_image)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>timestamp ()](#apidoc.element.cloudinary.utils.timestamp)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>updateable_resource_params (options, params)](#apidoc.element.cloudinary.utils.updateable_resource_params)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>url (public_id, options)](#apidoc.element.cloudinary.utils.url)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>v1_adapters (exports, v1, mapping)](#apidoc.element.cloudinary.utils.v1_adapters)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>video_thumbnail_url (public_id, options)](#apidoc.element.cloudinary.utils.video_thumbnail_url)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>video_url (public_id, options)](#apidoc.element.cloudinary.utils.video_url)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>webhook_signature (data, timestamp, options)](#apidoc.element.cloudinary.utils.webhook_signature)
1.  [function <span class="apidocSignatureSpan">cloudinary.utils.</span>zip_download_url (tag, options)](#apidoc.element.cloudinary.utils.zip_download_url)
1.  object <span class="apidocSignatureSpan">cloudinary.utils.</span>DEFAULT_POSTER_OPTIONS
1.  object <span class="apidocSignatureSpan">cloudinary.utils.</span>DEFAULT_VIDEO_SOURCE_TYPES
1.  string <span class="apidocSignatureSpan">cloudinary.utils.</span>AKAMAI_SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.utils.</span>CF_SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.utils.</span>OLD_AKAMAI_SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.utils.</span>SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.utils.</span>USER_AGENT
1.  string <span class="apidocSignatureSpan">cloudinary.utils.</span>VERSION
1.  string <span class="apidocSignatureSpan">cloudinary.utils.</span>userPlatform

#### [module cloudinary.v2](#apidoc.module.cloudinary.v2)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.</span>PreloadedFile (file_info)](#apidoc.element.cloudinary.v2.PreloadedFile)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.</span>cloudinary_js_config ()](#apidoc.element.cloudinary.v2.cloudinary_js_config)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.</span>config (new_config, new_value)](#apidoc.element.cloudinary.v2.config)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.</span>image (source, options)](#apidoc.element.cloudinary.v2.image)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.</span>url (public_id, options)](#apidoc.element.cloudinary.v2.url)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.</span>video (public_id, options)](#apidoc.element.cloudinary.v2.video)
1.  object <span class="apidocSignatureSpan">cloudinary.v2.</span>api
1.  object <span class="apidocSignatureSpan">cloudinary.v2.</span>uploader
1.  object <span class="apidocSignatureSpan">cloudinary.v2.</span>utils
1.  string <span class="apidocSignatureSpan">cloudinary.v2.</span>AKAMAI_SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.v2.</span>BLANK
1.  string <span class="apidocSignatureSpan">cloudinary.v2.</span>CF_SHARED_CDN
1.  string <span class="apidocSignatureSpan">cloudinary.v2.</span>SHARED_CDN

#### [module cloudinary.v2.api](#apidoc.module.cloudinary.v2.api)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_streaming_profile ()](#apidoc.element.cloudinary.v2.api.create_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_transformation ()](#apidoc.element.cloudinary.v2.api.create_transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_upload_mapping ()](#apidoc.element.cloudinary.v2.api.create_upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_upload_preset ()](#apidoc.element.cloudinary.v2.api.create_upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_all_resources ()](#apidoc.element.cloudinary.v2.api.delete_all_resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_derived_resources ()](#apidoc.element.cloudinary.v2.api.delete_derived_resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_resources ()](#apidoc.element.cloudinary.v2.api.delete_resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_resources_by_prefix ()](#apidoc.element.cloudinary.v2.api.delete_resources_by_prefix)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_resources_by_tag ()](#apidoc.element.cloudinary.v2.api.delete_resources_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_streaming_profile ()](#apidoc.element.cloudinary.v2.api.delete_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_transformation ()](#apidoc.element.cloudinary.v2.api.delete_transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_upload_mapping ()](#apidoc.element.cloudinary.v2.api.delete_upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_upload_preset ()](#apidoc.element.cloudinary.v2.api.delete_upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>get_streaming_profile ()](#apidoc.element.cloudinary.v2.api.get_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>list_streaming_profiles ()](#apidoc.element.cloudinary.v2.api.list_streaming_profiles)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>ping ()](#apidoc.element.cloudinary.v2.api.ping)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>publish_by_ids ()](#apidoc.element.cloudinary.v2.api.publish_by_ids)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>publish_by_prefix ()](#apidoc.element.cloudinary.v2.api.publish_by_prefix)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>publish_by_tag ()](#apidoc.element.cloudinary.v2.api.publish_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resource ()](#apidoc.element.cloudinary.v2.api.resource)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resource_types ()](#apidoc.element.cloudinary.v2.api.resource_types)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources ()](#apidoc.element.cloudinary.v2.api.resources)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_context ()](#apidoc.element.cloudinary.v2.api.resources_by_context)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_ids ()](#apidoc.element.cloudinary.v2.api.resources_by_ids)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_moderation ()](#apidoc.element.cloudinary.v2.api.resources_by_moderation)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_tag ()](#apidoc.element.cloudinary.v2.api.resources_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>restore ()](#apidoc.element.cloudinary.v2.api.restore)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>root_folders ()](#apidoc.element.cloudinary.v2.api.root_folders)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>sub_folders ()](#apidoc.element.cloudinary.v2.api.sub_folders)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>tags ()](#apidoc.element.cloudinary.v2.api.tags)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>transformation ()](#apidoc.element.cloudinary.v2.api.transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>transformations ()](#apidoc.element.cloudinary.v2.api.transformations)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update ()](#apidoc.element.cloudinary.v2.api.update)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_resources_access_mode_by_ids ()](#apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_ids)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_resources_access_mode_by_prefix ()](#apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_prefix)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_resources_access_mode_by_tag ()](#apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_streaming_profile ()](#apidoc.element.cloudinary.v2.api.update_streaming_profile)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_transformation ()](#apidoc.element.cloudinary.v2.api.update_transformation)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_upload_mapping ()](#apidoc.element.cloudinary.v2.api.update_upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_upload_preset ()](#apidoc.element.cloudinary.v2.api.update_upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_mapping ()](#apidoc.element.cloudinary.v2.api.upload_mapping)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_mappings ()](#apidoc.element.cloudinary.v2.api.upload_mappings)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_preset ()](#apidoc.element.cloudinary.v2.api.upload_preset)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_presets ()](#apidoc.element.cloudinary.v2.api.upload_presets)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>usage ()](#apidoc.element.cloudinary.v2.api.usage)

#### [module cloudinary.v2.uploader](#apidoc.module.cloudinary.v2.uploader)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>add_context ()](#apidoc.element.cloudinary.v2.uploader.add_context)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>add_tag ()](#apidoc.element.cloudinary.v2.uploader.add_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>create_archive ()](#apidoc.element.cloudinary.v2.uploader.create_archive)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>create_zip ()](#apidoc.element.cloudinary.v2.uploader.create_zip)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>destroy ()](#apidoc.element.cloudinary.v2.uploader.destroy)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>direct_upload (callback_url, options)](#apidoc.element.cloudinary.v2.uploader.direct_upload)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>explicit ()](#apidoc.element.cloudinary.v2.uploader.explicit)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>explode ()](#apidoc.element.cloudinary.v2.uploader.explode)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>generate_sprite ()](#apidoc.element.cloudinary.v2.uploader.generate_sprite)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>image_upload_tag (field, options)](#apidoc.element.cloudinary.v2.uploader.image_upload_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>multi ()](#apidoc.element.cloudinary.v2.uploader.multi)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>remove_all_context ()](#apidoc.element.cloudinary.v2.uploader.remove_all_context)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>remove_all_tags ()](#apidoc.element.cloudinary.v2.uploader.remove_all_tags)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>remove_tag ()](#apidoc.element.cloudinary.v2.uploader.remove_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>rename ()](#apidoc.element.cloudinary.v2.uploader.rename)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>replace_tag ()](#apidoc.element.cloudinary.v2.uploader.replace_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>text ()](#apidoc.element.cloudinary.v2.uploader.text)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>unsigned_image_upload_tag (field, upload_preset, options)](#apidoc.element.cloudinary.v2.uploader.unsigned_image_upload_tag)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>unsigned_upload ()](#apidoc.element.cloudinary.v2.uploader.unsigned_upload)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>unsigned_upload_stream ()](#apidoc.element.cloudinary.v2.uploader.unsigned_upload_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload ()](#apidoc.element.cloudinary.v2.uploader.upload)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_chunked ()](#apidoc.element.cloudinary.v2.uploader.upload_chunked)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_chunked_stream ()](#apidoc.element.cloudinary.v2.uploader.upload_chunked_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_large ()](#apidoc.element.cloudinary.v2.uploader.upload_large)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_large_part ()](#apidoc.element.cloudinary.v2.uploader.upload_large_part)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_stream ()](#apidoc.element.cloudinary.v2.uploader.upload_stream)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_tag_params (options)](#apidoc.element.cloudinary.v2.uploader.upload_tag_params)
1.  [function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_url (options)](#apidoc.element.cloudinary.v2.uploader.upload_url)



# <a name="apidoc.module.cloudinary"></a>[module cloudinary](#apidoc.module.cloudinary)

#### <a name="apidoc.element.cloudinary.PreloadedFile"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>PreloadedFile (file_info)](#apidoc.element.cloudinary.PreloadedFile)
- description and source-code
```javascript
function PreloadedFile(file_info) {
  var matches, public_id_and_format;
  matches = file_info.match(PRELOADED_CLOUDINARY_PATH);
  if (!matches) {
    throw "Invalid preloaded file info";
  }
  this.resource_type = matches[1];
  this.type = matches[2];
  this.version = matches[3];
  this.filename = matches[4];
  this.signature = matches[5];
  public_id_and_format = this.split_format(this.filename);
  this.public_id = public_id_and_format[0];
  this.format = public_id_and_format[1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.cloudinary_js_config"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>cloudinary_js_config ()](#apidoc.element.cloudinary.cloudinary_js_config)
- description and source-code
```javascript
cloudinary_js_config = function () {
  var j, len, param, params, value;
  params = {};
  for (j = 0, len = CLOUDINARY_JS_CONFIG_PARAMS.length; j < len; j++) {
    param = CLOUDINARY_JS_CONFIG_PARAMS[j];
    value = config()[param];
    if (value != null) {
      params[param] = value;
    }
  }
  return "<script type='text/javascript'>\n" + "$.cloudinary.config(" + JSON.stringify(params) + ");\n" + "</script>\n";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.config"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>config (new_config, new_value)](#apidoc.element.cloudinary.config)
- description and source-code
```javascript
config = function (new_config, new_value) {
  var cloudinary_url, k, ref, uri, v;
  if ((cloudinary_config == null) || new_config === true) {
    cloudinary_url = process.env.CLOUDINARY_URL;
    if (cloudinary_url != null) {
      uri = require('url').parse(cloudinary_url, true);
      cloudinary_config = {
        cloud_name: uri.host,
        api_key: uri.auth && uri.auth.split(":")[0],
        api_secret: uri.auth && uri.auth.split(":")[1],
        private_cdn: uri.pathname != null,
        secure_distribution: uri.pathname && uri.pathname.substring(1)
      };
      if (uri.query != null) {
        ref = uri.query;
        for (k in ref) {
          v = ref[k];
          if (isNestedKey(k)) {
            putNestedValue(cloudinary_config, k, v);
          } else {
            cloudinary_config[k] = v;
          }
        }
      }
    } else {
      cloudinary_config = {};
    }
  }
  if (!_.isUndefined(new_value)) {
    cloudinary_config[new_config] = new_value;
  } else if (_.isString(new_config)) {
    return cloudinary_config[new_config];
  } else if (_.isObject(new_config)) {
    _.extend(cloudinary_config, new_config);
  }
  return cloudinary_config;
}
```
- example usage
```shell
...
## Usage

### Configuration

Each request for building a URL of a remote cloud resource must have the 'cloud_name' parameter set.
Each request to our secure APIs (e.g., image uploads, eager sprite generation) must have the 'api_key' and 'api_secret' parameters
 set. See [API, URLs and access identifiers](http://cloudinary.com/documentation/api_and_access_identifiers) for more details.

Setting the 'cloud_name', 'api_key' and 'api_secret' parameters can be done either directly in each call to a Cloudinary method,
by calling the cloudinary.config(), or by using the CLOUDINARY_URL environment variable.

### Overriding the request agent
To override the request agent pass the agent into any method that makes a
request and it will be used instead of the normal https agent. e.g
'''js

cloudinary.uploader.upload_stream(
...
```

#### <a name="apidoc.element.cloudinary.image"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>image (source, options)](#apidoc.element.cloudinary.image)
- description and source-code
```javascript
image = function (source, options) {
  var responsive, html, current_class, classes;
  options = _.extend({}, options);
  source = cloudinary.utils.url(source, options);
  if ("html_width" in options) options["width"] = cloudinary.utils.option_consume(options, "html_width");
  if ("html_height" in options) options["height"] = cloudinary.utils.option_consume(options, "html_height");

  client_hints = cloudinary.utils.option_consume(options, "client_hints", cloudinary.config().client_hints);
  responsive = cloudinary.utils.option_consume(options, "responsive");
  hidpi = cloudinary.utils.option_consume(options, "hidpi");

  if ((responsive || hidpi) && !client_hints) {
    options["data-src"] = source;
    classes = [responsive ? "cld-responsive" : "cld-hidpi"];
    current_class = cloudinary.utils.option_consume(options, "class");
    if (current_class) classes.push(current_class);
    options["class"] = classes.join(" ");
    source = cloudinary.utils.option_consume(options, "responsive_placeholder", cloudinary.config().responsive_placeholder);
    if (source == "blank") {
      source = cloudinary.BLANK;
    }
  }
  html = "<img ";
  if (source) html += "src='" + source + "' ";
  html += cloudinary.utils.html_attrs(options) + "/>";
  return html;
}
```
- example usage
```shell
...

### cloudinary.image

Returns an html image tag pointing to Cloudinary.

Usage:

    cloudinary.image("sample", {format: "png", width: 100, height: 100, crop: "fill"})

    // <img src='http://res.cloudinary.com/demo/image/upload/c_fill,h_100,w_100/sample.png' height='100' width='100'/>

### Samples

You can find our simple and ready-to-use samples projects, along with documentation in the [samples folder](https://github.com/cloudinary
/cloudinary_npm/tree/master/samples).
Please consult with the [README file](https://github.com/cloudinary/cloudinary_npm/blob/master/samples/README.md), for usage and
 explanations.
...
```

#### <a name="apidoc.element.cloudinary.upload_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>upload_stream (options)](#apidoc.element.cloudinary.upload_stream)
- description and source-code
```javascript
upload_stream = function (options) {
  this.boundary = options.boundary;
  stream.Transform.call(this, options);
}
```
- example usage
```shell
...
Setting the 'cloud_name', 'api_key' and 'api_secret' parameters can be done either directly in each call to a Cloudinary method,
by calling the cloudinary.config(), or by using the CLOUDINARY_URL environment variable.

### Overriding the request agent
To override the request agent pass the agent into any method that makes a
request and it will be used instead of the normal https agent. e.g
'''js

cloudinary.uploader.upload_stream(
  function(result) { console.log(result); },
  { agent: myAgent }
);

'''

### Embedding and transforming images
...
```

#### <a name="apidoc.element.cloudinary.url"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>url (public_id, options)](#apidoc.element.cloudinary.url)
- description and source-code
```javascript
url = function (public_id, options) {
  options = _.extend({}, options);
  return cloudinary.utils.url(public_id, options);
}
```
- example usage
```shell
...

### Embedding and transforming images

Any image uploaded to Cloudinary can be transformed and embedded using powerful view helper methods:

The following example generates the url for accessing an uploaded 'sample' image while transforming it to fill a 100x150 rectangle
:

    cloudinary.url("sample.jpg", {width: 100, height: 150, crop: "fill"})

Another example, emedding a smaller version of an uploaded image while generating a 90x90 face detection based thumbnail:

    cloudinary.url("woman.jpg", {width: 90, height: 90, crop: "thumb", gravity: "face"})

You can provide either a Facebook name or a numeric ID of a Facebook profile or a fan page.
...
```

#### <a name="apidoc.element.cloudinary.video"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>video (public_id, options)](#apidoc.element.cloudinary.video)
- description and source-code
```javascript
video = function (public_id, options) {
  var src, video_options, fallback, source_transformation, source_types, source, multi_source, html;
  options = _.extend({}, options);
  public_id = public_id.replace(/\.(mp4|ogv|webm)$/, '');
  source_types = cloudinary.utils.option_consume(options, 'source_types', []);
  source_transformation = cloudinary.utils.option_consume(options, 'source_transformation', {});
  fallback = cloudinary.utils.option_consume(options, 'fallback_content', '');

  if (source_types.length === 0) source_types = cloudinary.utils.DEFAULT_VIDEO_SOURCE_TYPES;
  video_options = _.cloneDeep(options);

  if (video_options.hasOwnProperty('poster')) {
    if (_.isPlainObject(video_options.poster)) {
      if (video_options.poster.hasOwnProperty('public_id')) {
        video_options.poster = cloudinary.utils.url(video_options.poster.public_id, video_options.poster);
      } else {
        video_options.poster = cloudinary.utils.url(public_id, _.extend({}, cloudinary.utils.DEFAULT_POSTER_OPTIONS, video_options
.poster));
      }
    }
  } else {
    video_options.poster = cloudinary.utils.url(public_id, _.extend({}, cloudinary.utils.DEFAULT_POSTER_OPTIONS, options));
  }

  if (!video_options.poster) delete video_options.poster;

  html = '<video ';

  if (!video_options.hasOwnProperty('resource_type')) video_options.resource_type = 'video';
  multi_source = _.isArray(source_types) && source_types.length > 1;
  source = public_id;
  if (!multi_source) {
    source = source + '.' + cloudinary.utils.build_array(source_types)[0];
  }
  src = cloudinary.utils.url(source, video_options);
  if (!multi_source) video_options.src = src;
  if (video_options.hasOwnProperty("html_width")) video_options.width = cloudinary.utils.option_consume(video_options, 'html_width
');
  if (video_options.hasOwnProperty("html_height")) video_options.height = cloudinary.utils.option_consume(video_options, 'html_height
');
  html = html + cloudinary.utils.html_attrs(video_options) + '>';
  if (multi_source) {
    var source_type, transformation, video_type, mime_type;
    for (var i = 0; i < source_types.length; i++) {
      source_type = source_types[i];
      transformation = source_transformation[source_type] || {};
      src = cloudinary.utils.url(source + "." + source_type, _.extend({resource_type: 'video'}, _.cloneDeep(options), _.cloneDeep
(transformation)));
      video_type = source_type === 'ogv' ? 'ogg' : source_type;
      mime_type = "video/" + video_type;
      html = html + '<source ' + cloudinary.utils.html_attrs({
        src: src,
        type: mime_type
      }) + '>';
    }
  }

  html = html + fallback;
  html = html + '</video>';
  return html;
}
```
- example usage
```shell
...
 *        source type the tag should include. defaults to webm, mp4 and ogv.
 * @param {String} [options.source_transformation] specific transformations
 *        to use for a specific source type.
 * @param {(String|Object)} [options.poster] image URL or
 *        poster options that may include a <tt>public_id</tt> key and
 *        poster-specific transformations
 * @example <caption>Example of generating a video tag:</caption>
 * $.cloudinary.video("mymovie.mp4");
 * $.cloudinary.video("mymovie.mp4", {source_types: 'webm'});
 * $.cloudinary.video("mymovie.ogv", {poster: "myspecialplaceholder.jpg"});
 * $.cloudinary.video("mymovie.webm", {source_types: ['webm', 'mp4'], poster: {effect: 'sepia'}});
 * @return {string} HTML video tag
 */
exports.video = function (public_id, options) {
var src, video_options, fallback, source_transformation, source_types, source, multi_source, html;
...
```



# <a name="apidoc.module.cloudinary.PreloadedFile"></a>[module cloudinary.PreloadedFile](#apidoc.module.cloudinary.PreloadedFile)

#### <a name="apidoc.element.cloudinary.PreloadedFile.PreloadedFile"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>PreloadedFile (file_info)](#apidoc.element.cloudinary.PreloadedFile.PreloadedFile)
- description and source-code
```javascript
function PreloadedFile(file_info) {
  var matches, public_id_and_format;
  matches = file_info.match(PRELOADED_CLOUDINARY_PATH);
  if (!matches) {
    throw "Invalid preloaded file info";
  }
  this.resource_type = matches[1];
  this.type = matches[2];
  this.version = matches[3];
  this.filename = matches[4];
  this.signature = matches[5];
  public_id_and_format = this.split_format(this.filename);
  this.public_id = public_id_and_format[0];
  this.format = public_id_and_format[1];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.PreloadedFile.prototype"></a>[module cloudinary.PreloadedFile.prototype](#apidoc.module.cloudinary.PreloadedFile.prototype)

#### <a name="apidoc.element.cloudinary.PreloadedFile.prototype.identifier"></a>[function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>identifier ()](#apidoc.element.cloudinary.PreloadedFile.prototype.identifier)
- description and source-code
```javascript
identifier = function () {
  return "v" + this.version + "/" + this.filename;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.PreloadedFile.prototype.is_valid"></a>[function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>is_valid ()](#apidoc.element.cloudinary.PreloadedFile.prototype.is_valid)
- description and source-code
```javascript
is_valid = function () {
  var expected_signature, public_id;
  public_id = this.resource_type === "raw" ? this.filename : this.public_id;
  expected_signature = utils.api_sign_request({
    public_id: this.public_id,
    version: this.version
  }, config().api_secret);
  return this.signature === expected_signature;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.PreloadedFile.prototype.split_format"></a>[function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>split_format (identifier)](#apidoc.element.cloudinary.PreloadedFile.prototype.split_format)
- description and source-code
```javascript
split_format = function (identifier) {
  var format, last_dot, public_id;
  last_dot = identifier.lastIndexOf(".");
  if (last_dot === -1) {
    return [identifier, null];
  }
  public_id = identifier.substr(0, last_dot);
  format = identifier.substr(last_dot + 1);
  return [public_id, format];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.PreloadedFile.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>toJSON ()](#apidoc.element.cloudinary.PreloadedFile.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  var key, ref, result, val;
  result = {};
  ref = this;
  for (key in ref) {
    val = ref[key];
    if (typeof val !== 'function') {
      result[key] = val;
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.PreloadedFile.prototype.toString"></a>[function <span class="apidocSignatureSpan">cloudinary.PreloadedFile.prototype.</span>toString ()](#apidoc.element.cloudinary.PreloadedFile.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return this.resource_type + "/" + this.type + "/v" + this.version + "/" + this.filename + "#" + this.signature;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.akamai"></a>[module cloudinary.akamai](#apidoc.module.cloudinary.akamai)

#### <a name="apidoc.element.cloudinary.akamai.generateAkamaiToken"></a>[function <span class="apidocSignatureSpan">cloudinary.akamai.</span>generateAkamaiToken (options)](#apidoc.element.cloudinary.akamai.generateAkamaiToken)
- description and source-code
```javascript
generateAkamaiToken = function (options) {
  var auth, expiration, key, ref, ref1, ref2, start, tokenName, tokenParts;
  key = (ref = options.key) != null ? ref : config().akamai_key;
  tokenName = (ref1 = options.tokenName) != null ? ref1 : "__cld_token__";
  expiration = options.end_time;
  if (expiration == null) {
    if (options.window == null) {
      start = (ref2 = options.start_time) != null ? ref2 : new Date();
      expiration = start + window;
    } else {
      throw "Must provide either end_time or window";
    }
  }
  tokenParts = [];
  if (options.ip != null) {
    tokenParts.push("ip=" + options.ip);
  }
  if (options.start_time != null) {
    tokenParts.push("st=" + options.start_time);
  }
  tokenParts.push("exp=" + expiration);
  tokenParts.push("acl=" + options.acl);
  auth = digest(tokenParts.join("~"), key);
  tokenParts.push("hmac=" + auth);
  return tokenName + "=" + (tokenParts.join('~'));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.api"></a>[module cloudinary.api](#apidoc.module.cloudinary.api)

#### <a name="apidoc.element.cloudinary.api.create_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>create_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.create_streaming_profile)
- description and source-code
```javascript
create_streaming_profile = function (name, callback, options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = utils.build_streaming_profiles_param(options);
  params["name"] = name;
  return call_api("post", 'streaming_profiles', params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.create_transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>create_transformation (name, definition, callback, options)](#apidoc.element.cloudinary.api.create_transformation)
- description and source-code
```javascript
create_transformation = function (name, definition, callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["transformations", name];
  return call_api("post", uri, {
    transformation: transformation_string(definition)
  }, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.create_upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>create_upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.create_upload_mapping)
- description and source-code
```javascript
create_upload_mapping = function (name, callback, options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = api.only(options, "template");
  params["folder"] = name;
  return call_api("post", 'upload_mappings', params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.create_upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>create_upload_preset (callback, options)](#apidoc.element.cloudinary.api.create_upload_preset)
- description and source-code
```javascript
create_upload_preset = function (callback, options) {
  var params, uri;
  if (options == null) {
    options = {};
  }
  uri = ["upload_presets"];
  params = utils.merge(utils.clear_blank(utils.build_upload_params(options)), api.only(options, "name", "unsigned", "disallow_public_id
"));
  return call_api("post", uri, params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_all_resources"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_all_resources (callback, options)](#apidoc.element.cloudinary.api.delete_all_resources)
- description and source-code
```javascript
delete_all_resources = function (callback, options) {
  var ref, ref1, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = (ref1 = options["type"]) != null ? ref1 : "upload";
  uri = ["resources", resource_type, type];
  return call_api("delete", uri, _.extend({
    all: true
  }, api.only(options, "keep_original", "next_cursor", "invalidate")), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_derived_resources"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_derived_resources (derived_resource_ids, callback, options)](#apidoc.element.cloudinary.api.delete_derived_resources)
- description and source-code
```javascript
delete_derived_resources = function (derived_resource_ids, callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["derived_resources"];
  return call_api("delete", uri, {
    "derived_resource_ids[]": derived_resource_ids
  }, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_resources"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_resources (public_ids, callback, options)](#apidoc.element.cloudinary.api.delete_resources)
- description and source-code
```javascript
delete_resources = function (public_ids, callback, options) {
  var ref, ref1, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = (ref1 = options["type"]) != null ? ref1 : "upload";
  uri = ["resources", resource_type, type];
  return call_api("delete", uri, _.extend({
    "public_ids[]": public_ids
  }, api.only(options, "keep_original", "invalidate")), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_resources_by_prefix"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_resources_by_prefix (prefix, callback, options)](#apidoc.element.cloudinary.api.delete_resources_by_prefix)
- description and source-code
```javascript
delete_resources_by_prefix = function (prefix, callback, options) {
  var ref, ref1, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = (ref1 = options["type"]) != null ? ref1 : "upload";
  uri = ["resources", resource_type, type];
  return call_api("delete", uri, _.extend({
    prefix: prefix
  }, api.only(options, "keep_original", "next_cursor", "invalidate")), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_resources_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_resources_by_tag (tag, callback, options)](#apidoc.element.cloudinary.api.delete_resources_by_tag)
- description and source-code
```javascript
delete_resources_by_tag = function (tag, callback, options) {
  var ref, resource_type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  uri = ["resources", resource_type, "tags", tag];
  return call_api("delete", uri, api.only(options, "keep_original", "next_cursor", "invalidate"), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.delete_streaming_profile)
- description and source-code
```javascript
delete_streaming_profile = function (name, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("delete", "streaming_profiles/" + name, {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_transformation (transformation, callback, options)](#apidoc.element.cloudinary.api.delete_transformation)
- description and source-code
```javascript
delete_transformation = function (transformation, callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["transformations", transformation_string(transformation)];
  return call_api("delete", uri, {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.delete_upload_mapping)
- description and source-code
```javascript
delete_upload_mapping = function (name, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("delete", 'upload_mappings', {
    folder: name
  }, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.delete_upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>delete_upload_preset (name, callback, options)](#apidoc.element.cloudinary.api.delete_upload_preset)
- description and source-code
```javascript
delete_upload_preset = function (name, callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["upload_presets", name];
  return call_api("delete", uri, {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.get_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>get_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.get_streaming_profile)
- description and source-code
```javascript
get_streaming_profile = function (name, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("get", "streaming_profiles/" + name, {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.list_streaming_profiles"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>list_streaming_profiles (callback, options)](#apidoc.element.cloudinary.api.list_streaming_profiles)
- description and source-code
```javascript
list_streaming_profiles = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("get", "streaming_profiles", {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.only"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>only ()](#apidoc.element.cloudinary.api.only)
- description and source-code
```javascript
only = function () {
  var hash, i, key, keys, len, result;
  hash = arguments[0], keys = 2 <= arguments.length ? slice.call(arguments, 1) : [];
  result = {};
  for (i = 0, len = keys.length; i < len; i++) {
    key = keys[i];
    if (hash[key] != null) {
      result[key] = hash[key];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.ping"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>ping (callback, options)](#apidoc.element.cloudinary.api.ping)
- description and source-code
```javascript
ping = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("get", ["ping"], {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.publish_by_ids"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>publish_by_ids (public_ids, callback, options)](#apidoc.element.cloudinary.api.publish_by_ids)
- description and source-code
```javascript
publish_by_ids = function (public_ids, callback, options) {
  if (options == null) {
    options = {};
  }
  return publishResource("public_ids", public_ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.publish_by_prefix"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>publish_by_prefix (prefix, callback, options)](#apidoc.element.cloudinary.api.publish_by_prefix)
- description and source-code
```javascript
publish_by_prefix = function (prefix, callback, options) {
  if (options == null) {
    options = {};
  }
  return publishResource("prefix", prefix, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.publish_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>publish_by_tag (tag, callback, options)](#apidoc.element.cloudinary.api.publish_by_tag)
- description and source-code
```javascript
publish_by_tag = function (tag, callback, options) {
  if (options == null) {
    options = {};
  }
  return publishResource("tag", tag, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.resource"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>resource (public_id, callback, options)](#apidoc.element.cloudinary.api.resource)
- description and source-code
```javascript
resource = function (public_id, callback, options) {
  var ref, ref1, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = (ref1 = options["type"]) != null ? ref1 : "upload";
  uri = ["resources", resource_type, type, public_id];
  return call_api("get", uri, api.only(options, "exif", "colors", "faces", "image_metadata", "pages", "phash", "coordinates", "max_results
"), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.resource_types"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>resource_types (callback, options)](#apidoc.element.cloudinary.api.resource_types)
- description and source-code
```javascript
resource_types = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("get", ["resources"], {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.resources"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>resources (callback, options)](#apidoc.element.cloudinary.api.resources)
- description and source-code
```javascript
resources = function (callback, options) {
  var ref, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = options["type"];
  uri = ["resources", resource_type];
  if (type != null) {
    uri.push(type);
  }
  if ((options.start_at != null) && Object.prototype.toString.call(options.start_at) === '[object Date]') {
    options.start_at = options.start_at.toUTCString();
  }
  return call_api("get", uri, api.only(options, "next_cursor", "max_results", "prefix", "tags", "context", "direction", "moderations
", "start_at"), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.resources_by_context"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_context (key, value, callback, options)](#apidoc.element.cloudinary.api.resources_by_context)
- description and source-code
```javascript
resources_by_context = function (key, value, callback, options) {
  var params, ref, resource_type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  uri = ["resources", resource_type, "context"];
  params = api.only(options, "next_cursor", "max_results", "tags", "context", "direction", "moderations");
  params.key = key;
  if (value != null) {
    params.value = value;
  }
  return call_api("get", uri, params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.resources_by_ids"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_ids (public_ids, callback, options)](#apidoc.element.cloudinary.api.resources_by_ids)
- description and source-code
```javascript
resources_by_ids = function (public_ids, callback, options) {
  var params, ref, ref1, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = (ref1 = options["type"]) != null ? ref1 : "upload";
  uri = ["resources", resource_type, type];
  params = api.only(options, "tags", "context", "moderations");
  params["public_ids[]"] = public_ids;
  return call_api("get", uri, params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.resources_by_moderation"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_moderation (kind, status, callback, options)](#apidoc.element.cloudinary.api.resources_by_moderation)
- description and source-code
```javascript
resources_by_moderation = function (kind, status, callback, options) {
  var ref, resource_type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  uri = ["resources", resource_type, "moderations", kind, status];
  return call_api("get", uri, api.only(options, "next_cursor", "max_results", "tags", "context", "direction", "moderations"), callback
, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.resources_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>resources_by_tag (tag, callback, options)](#apidoc.element.cloudinary.api.resources_by_tag)
- description and source-code
```javascript
resources_by_tag = function (tag, callback, options) {
  var ref, resource_type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  uri = ["resources", resource_type, "tags", tag];
  return call_api("get", uri, api.only(options, "next_cursor", "max_results", "tags", "context", "direction", "moderations"), callback
, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.restore"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>restore (public_ids, callback, options)](#apidoc.element.cloudinary.api.restore)
- description and source-code
```javascript
restore = function (public_ids, callback, options) {
  var ref, ref1, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = (ref1 = options["type"]) != null ? ref1 : "upload";
  uri = ["resources", resource_type, type, "restore"];
  return call_api("post", uri, {
    public_ids: public_ids
  }, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.root_folders"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>root_folders (callback, options)](#apidoc.element.cloudinary.api.root_folders)
- description and source-code
```javascript
root_folders = function (callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["folders"];
  return call_api("get", uri, {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.sub_folders"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>sub_folders (path, callback, options)](#apidoc.element.cloudinary.api.sub_folders)
- description and source-code
```javascript
sub_folders = function (path, callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["folders", path];
  return call_api("get", uri, {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.tags"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>tags (callback, options)](#apidoc.element.cloudinary.api.tags)
- description and source-code
```javascript
tags = function (callback, options) {
  var ref, resource_type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  uri = ["tags", resource_type];
  return call_api("get", uri, api.only(options, "next_cursor", "max_results", "prefix"), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>transformation (transformation, callback, options)](#apidoc.element.cloudinary.api.transformation)
- description and source-code
```javascript
transformation = function (transformation, callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["transformations", transformation_string(transformation)];
  return call_api("get", uri, api.only(options, "next_cursor", "max_results"), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.transformations"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>transformations (callback, options)](#apidoc.element.cloudinary.api.transformations)
- description and source-code
```javascript
transformations = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("get", ["transformations"], api.only(options, "next_cursor", "max_results"), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.update"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update (public_id, callback, options)](#apidoc.element.cloudinary.api.update)
- description and source-code
```javascript
update = function (public_id, callback, options) {
  var params, ref, ref1, resource_type, type, uri;
  if (options == null) {
    options = {};
  }
  resource_type = (ref = options["resource_type"]) != null ? ref : "image";
  type = (ref1 = options["type"]) != null ? ref1 : "upload";
  uri = ["resources", resource_type, type, public_id];
  params = utils.updateable_resource_params(options);
  if (options.moderation_status != null) {
    params.moderation_status = options.moderation_status;
  }
  return call_api("post", uri, params, callback, options);
}
```
- example usage
```shell
...
var config, crypto, digest;

crypto = require('crypto');

config = require('./config');

digest = function(message, key) {
  return crypto.createHmac("sha256", new Buffer(key, "hex")).update(message).digest('hex');
};

exports.generateAkamaiToken = function(options) {
  var auth, expiration, key, ref, ref1, ref2, start, tokenName, tokenParts;
  key = (ref = options.key) != null ? ref : config().akamai_key;
  tokenName = (ref1 = options.tokenName) != null ? ref1 : "__cld_token__";
  expiration = options.end_time;
...
```

#### <a name="apidoc.element.cloudinary.api.update_resources_access_mode_by_ids"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update_resources_access_mode_by_ids (access_mode, ids, callback, options)](#apidoc.element.cloudinary.api.update_resources_access_mode_by_ids)
- description and source-code
```javascript
update_resources_access_mode_by_ids = function (access_mode, ids, callback, options) {
  if (options == null) {
    options = {};
  }
  return update_resources_access_mode(access_mode, "public_ids[]", ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.update_resources_access_mode_by_prefix"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update_resources_access_mode_by_prefix (access_mode, prefix, callback, options)](#apidoc.element.cloudinary.api.update_resources_access_mode_by_prefix)
- description and source-code
```javascript
update_resources_access_mode_by_prefix = function (access_mode, prefix, callback, options) {
  if (options == null) {
    options = {};
  }
  return update_resources_access_mode(access_mode, "prefix", prefix, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.update_resources_access_mode_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update_resources_access_mode_by_tag (access_mode, tag, callback, options)](#apidoc.element.cloudinary.api.update_resources_access_mode_by_tag)
- description and source-code
```javascript
update_resources_access_mode_by_tag = function (access_mode, tag, callback, options) {
  if (options == null) {
    options = {};
  }
  return update_resources_access_mode(access_mode, "tag", tag, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.update_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update_streaming_profile (name, callback, options)](#apidoc.element.cloudinary.api.update_streaming_profile)
- description and source-code
```javascript
update_streaming_profile = function (name, callback, options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = utils.build_streaming_profiles_param(options);
  return call_api("put", "streaming_profiles/" + name, params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.update_transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update_transformation (transformation, updates, callback, options)](#apidoc.element.cloudinary.api.update_transformation)
- description and source-code
```javascript
update_transformation = function (transformation, updates, callback, options) {
  var params, uri;
  if (options == null) {
    options = {};
  }
  uri = ["transformations", transformation_string(transformation)];
  params = api.only(updates, "allowed_for_strict");
  if (updates.unsafe_update != null) {
    params.unsafe_update = transformation_string(updates.unsafe_update);
  }
  return call_api("put", uri, params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.update_upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update_upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.update_upload_mapping)
- description and source-code
```javascript
update_upload_mapping = function (name, callback, options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = api.only(options, "template");
  params["folder"] = name;
  return call_api("put", 'upload_mappings', params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.update_upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>update_upload_preset (name, callback, options)](#apidoc.element.cloudinary.api.update_upload_preset)
- description and source-code
```javascript
update_upload_preset = function (name, callback, options) {
  var params, uri;
  if (options == null) {
    options = {};
  }
  uri = ["upload_presets", name];
  params = utils.merge(utils.clear_blank(utils.build_upload_params(options)), api.only(options, "unsigned", "disallow_public_id"));
  return call_api("put", uri, params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_mapping (name, callback, options)](#apidoc.element.cloudinary.api.upload_mapping)
- description and source-code
```javascript
upload_mapping = function (name, callback, options) {
  if (name == null) {
    name = null;
  }
  if (options == null) {
    options = {};
  }
  return call_api("get", 'upload_mappings', {
    folder: name
  }, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.upload_mappings"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_mappings (callback, options)](#apidoc.element.cloudinary.api.upload_mappings)
- description and source-code
```javascript
upload_mappings = function (callback, options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = api.only(options, "next_cursor", "max_results");
  return call_api("get", "upload_mappings", params, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_preset (name, callback, options)](#apidoc.element.cloudinary.api.upload_preset)
- description and source-code
```javascript
upload_preset = function (name, callback, options) {
  var uri;
  if (options == null) {
    options = {};
  }
  uri = ["upload_presets", name];
  return call_api("get", uri, {}, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.upload_presets"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>upload_presets (callback, options)](#apidoc.element.cloudinary.api.upload_presets)
- description and source-code
```javascript
upload_presets = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("get", ["upload_presets"], api.only(options, "next_cursor", "max_results"), callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.api.usage"></a>[function <span class="apidocSignatureSpan">cloudinary.api.</span>usage (callback, options)](#apidoc.element.cloudinary.api.usage)
- description and source-code
```javascript
usage = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("get", ["usage"], {}, callback, options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.upload_stream"></a>[module cloudinary.upload_stream](#apidoc.module.cloudinary.upload_stream)

#### <a name="apidoc.element.cloudinary.upload_stream.upload_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.</span>upload_stream (options)](#apidoc.element.cloudinary.upload_stream.upload_stream)
- description and source-code
```javascript
upload_stream = function (options) {
  this.boundary = options.boundary;
  stream.Transform.call(this, options);
}
```
- example usage
```shell
...
Setting the 'cloud_name', 'api_key' and 'api_secret' parameters can be done either directly in each call to a Cloudinary method,
by calling the cloudinary.config(), or by using the CLOUDINARY_URL environment variable.

### Overriding the request agent
To override the request agent pass the agent into any method that makes a
request and it will be used instead of the normal https agent. e.g
'''js

cloudinary.uploader.upload_stream(
  function(result) { console.log(result); },
  { agent: myAgent }
);

'''

### Embedding and transforming images
...
```

#### <a name="apidoc.element.cloudinary.upload_stream.super_"></a>[function <span class="apidocSignatureSpan">cloudinary.upload_stream.</span>super_ (options)](#apidoc.element.cloudinary.upload_stream.super_)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform))
    return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function')
      this._transform = options.transform;

    if (typeof options.flush === 'function')
      this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function() {
    if (typeof this._flush === 'function')
      this._flush(function(er) {
        done(stream, er);
      });
    else
      done(stream);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.upload_stream.prototype"></a>[module cloudinary.upload_stream.prototype](#apidoc.module.cloudinary.upload_stream.prototype)

#### <a name="apidoc.element.cloudinary.upload_stream.prototype._flush"></a>[function <span class="apidocSignatureSpan">cloudinary.upload_stream.prototype.</span>_flush (next)](#apidoc.element.cloudinary.upload_stream.prototype._flush)
- description and source-code
```javascript
_flush = function (next) {
  this.push(new Buffer("\r\n", 'ascii'));
  this.push(new Buffer("--" + this.boundary + "--", 'ascii'));
  return next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.upload_stream.prototype._transform"></a>[function <span class="apidocSignatureSpan">cloudinary.upload_stream.prototype.</span>_transform (data, encoding, next)](#apidoc.element.cloudinary.upload_stream.prototype._transform)
- description and source-code
```javascript
_transform = function (data, encoding, next) {
  var buffer;
  buffer = (Buffer.isBuffer(data) ? data : new Buffer(data, encoding));
  this.push(buffer);
  next();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.uploader"></a>[module cloudinary.uploader](#apidoc.module.cloudinary.uploader)

#### <a name="apidoc.element.cloudinary.uploader.add_context"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>add_context (context, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.add_context)
- description and source-code
```javascript
add_context = function (context, public_ids, callback, options) {
  if (public_ids == null) {
    public_ids = [];
  }
  if (options == null) {
    options = {};
  }
  return call_context_api(context, 'add', public_ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.add_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>add_tag (tag, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.add_tag)
- description and source-code
```javascript
add_tag = function (tag, public_ids, callback, options) {
  var command, exclusive;
  if (public_ids == null) {
    public_ids = [];
  }
  if (options == null) {
    options = {};
  }
  exclusive = utils.option_consume("exclusive", options);
  command = exclusive ? "set_exclusive" : "add";
  return call_tags_api(tag, command, public_ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.create_archive"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>create_archive (callback, options, target_format)](#apidoc.element.cloudinary.uploader.create_archive)
- description and source-code
```javascript
create_archive = function (callback, options, target_format) {
  if (options == null) {
    options = {};
  }
  if (target_format == null) {
    target_format = null;
  }
  return call_api("generate_archive", callback, options, function() {
    var opt;
    opt = utils.archive_params(options);
    if (target_format) {
      opt.target_format = target_format;
    }
    return [opt];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.create_zip"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>create_zip (callback, options)](#apidoc.element.cloudinary.uploader.create_zip)
- description and source-code
```javascript
create_zip = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return exports.create_archive(callback, options, "zip");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.destroy"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>destroy (public_id, callback, options)](#apidoc.element.cloudinary.uploader.destroy)
- description and source-code
```javascript
destroy = function (public_id, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("destroy", callback, options, function() {
    return [
      {
        timestamp: utils.timestamp(),
        type: options.type,
        invalidate: options.invalidate,
        public_id: public_id
      }
    ];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.direct_upload"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>direct_upload (callback_url, options)](#apidoc.element.cloudinary.uploader.direct_upload)
- description and source-code
```javascript
direct_upload = function (callback_url, options) {
  var api_url, params;
  if (options == null) {
    options = {};
  }
  params = build_upload_params(_.extend({
    callback: callback_url
  }, options));
  params = utils.process_request_params(params, options);
  api_url = utils.api_url("upload", options);
  return {
    hidden_fields: params,
    form_attrs: {
      action: api_url,
      method: "POST",
      enctype: "multipart/form-data"
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.explicit"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>explicit (public_id, callback, options)](#apidoc.element.cloudinary.uploader.explicit)
- description and source-code
```javascript
explicit = function (public_id, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("explicit", callback, options, function() {
    return utils.build_explicit_api_params(public_id, options);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.explode"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>explode (public_id, callback, options)](#apidoc.element.cloudinary.uploader.explode)
- description and source-code
```javascript
explode = function (public_id, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("explode", callback, options, function() {
    var transformation;
    transformation = utils.generate_transformation_string(_.extend({}, options));
    return [
      {
        timestamp: utils.timestamp(),
        public_id: public_id,
        transformation: transformation,
        format: options.format,
        type: options.type,
        notification_url: options.notification_url
      }
    ];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.generate_sprite"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>generate_sprite (tag, callback, options)](#apidoc.element.cloudinary.uploader.generate_sprite)
- description and source-code
```javascript
generate_sprite = function (tag, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("sprite", callback, options, function() {
    var transformation;
    transformation = utils.generate_transformation_string(_.extend({}, options, {
      fetch_format: options.format
    }));
    return [
      {
        timestamp: utils.timestamp(),
        tag: tag,
        transformation: transformation,
        async: options.async,
        notification_url: options.notification_url
      }
    ];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.image_upload_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>image_upload_tag (field, options)](#apidoc.element.cloudinary.uploader.image_upload_tag)
- description and source-code
```javascript
image_upload_tag = function (field, options) {
  var html_options, ref, tag_options;
  if (options == null) {
    options = {};
  }
  html_options = (ref = options.html) != null ? ref : {};
  tag_options = _.extend({
    type: "file",
    name: "file",
    "data-url": exports.upload_url(options),
    "data-form-data": exports.upload_tag_params(options),
    "data-cloudinary-field": field,
    "data-max-chunk-size": options.chunk_size,
    "class": [html_options["class"], "cloudinary-fileupload"].join(" ")
  }, html_options);
  return '<input ' + utils.html_attrs(tag_options) + '/>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.multi"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>multi (tag, callback, options)](#apidoc.element.cloudinary.uploader.multi)
- description and source-code
```javascript
multi = function (tag, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("multi", callback, options, function() {
    var transformation;
    transformation = utils.generate_transformation_string(_.extend({}, options));
    return [
      {
        timestamp: utils.timestamp(),
        tag: tag,
        transformation: transformation,
        format: options.format,
        async: options.async,
        notification_url: options.notification_url
      }
    ];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.remove_all_context"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>remove_all_context (public_ids, callback, options)](#apidoc.element.cloudinary.uploader.remove_all_context)
- description and source-code
```javascript
remove_all_context = function (public_ids, callback, options) {
  if (public_ids == null) {
    public_ids = [];
  }
  if (options == null) {
    options = {};
  }
  return call_context_api(null, 'remove_all', public_ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.remove_all_tags"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>remove_all_tags (public_ids, callback, options)](#apidoc.element.cloudinary.uploader.remove_all_tags)
- description and source-code
```javascript
remove_all_tags = function (public_ids, callback, options) {
  if (public_ids == null) {
    public_ids = [];
  }
  if (options == null) {
    options = {};
  }
  return call_tags_api(null, "remove_all", public_ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.remove_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>remove_tag (tag, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.remove_tag)
- description and source-code
```javascript
remove_tag = function (tag, public_ids, callback, options) {
  if (public_ids == null) {
    public_ids = [];
  }
  if (options == null) {
    options = {};
  }
  return call_tags_api(tag, "remove", public_ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.rename"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>rename (from_public_id, to_public_id, callback, options)](#apidoc.element.cloudinary.uploader.rename)
- description and source-code
```javascript
rename = function (from_public_id, to_public_id, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("rename", callback, options, function() {
    return [
      {
        timestamp: utils.timestamp(),
        type: options.type,
        from_public_id: from_public_id,
        to_public_id: to_public_id,
        overwrite: options.overwrite,
        invalidate: options.invalidate,
        to_type: options.to_type
      }
    ];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.replace_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>replace_tag (tag, public_ids, callback, options)](#apidoc.element.cloudinary.uploader.replace_tag)
- description and source-code
```javascript
replace_tag = function (tag, public_ids, callback, options) {
  if (public_ids == null) {
    public_ids = [];
  }
  if (options == null) {
    options = {};
  }
  return call_tags_api(tag, "replace", public_ids, callback, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.text"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>text (text, callback, options)](#apidoc.element.cloudinary.uploader.text)
- description and source-code
```javascript
text = function (text, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("text", callback, options, function() {
    var j, k, len, params;
    params = {
      timestamp: utils.timestamp(),
      text: text
    };
    for (j = 0, len = TEXT_PARAMS.length; j < len; j++) {
      k = TEXT_PARAMS[j];
      if (options[k] != null) {
        params[k] = options[k];
      }
    }
    return [params];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.unsigned_image_upload_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>unsigned_image_upload_tag (field, upload_preset, options)](#apidoc.element.cloudinary.uploader.unsigned_image_upload_tag)
- description and source-code
```javascript
unsigned_image_upload_tag = function (field, upload_preset, options) {
  if (options == null) {
    options = {};
  }
  return exports.image_upload_tag(field, utils.merge(options, {
    unsigned: true,
    upload_preset: upload_preset
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.unsigned_upload"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>unsigned_upload (file, upload_preset, callback, options)](#apidoc.element.cloudinary.uploader.unsigned_upload)
- description and source-code
```javascript
unsigned_upload = function (file, upload_preset, callback, options) {
  if (options == null) {
    options = {};
  }
  return exports.upload(file, callback, utils.merge(options, {
    unsigned: true,
    upload_preset: upload_preset
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.unsigned_upload_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>unsigned_upload_stream (upload_preset, callback, options)](#apidoc.element.cloudinary.uploader.unsigned_upload_stream)
- description and source-code
```javascript
unsigned_upload_stream = function (upload_preset, callback, options) {
  if (options == null) {
    options = {};
  }
  return exports.upload_stream(callback, utils.merge(options, {
    unsigned: true,
    upload_preset: upload_preset
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.upload"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload (file, callback, options)](#apidoc.element.cloudinary.uploader.upload)
- description and source-code
```javascript
upload = function (file, callback, options) {
  if (options == null) {
    options = {};
  }
  return call_api("upload", callback, options, function() {
    var params;
    params = build_upload_params(options);
    if ((file != null) && file.match(/^ftp:|^https?:|^s3:|^data:[^;]*;base64,([a-zA-Z0-9\/+\n=]+)$/)) {
      return [
        params, {
          file: file
        }
      ];
    } else {
      return [params, {}, file];
    }
  });
}
```
- example usage
```shell
...

Assuming you have your Cloudinary configuration parameters defined ('cloud_name', 'api_key', 'api_secret'), uploading to Cloudinary
 is very simple.

The following example uploads a local JPG to the cloud:

	var cloudinary = require('cloudinary')

   cloudinary.uploader.upload("my_picture.jpg", function(result) { console.log(result) })

Below is an example of an upload's result:

	{ public_id: '4srvcynxrf5j87niqcx6w',
	  version: 1340625837,
	  signature: '01234567890abcdef01234567890abcdef012345',
	  width: 200,
...
```

#### <a name="apidoc.element.cloudinary.uploader.upload_chunked"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_chunked (path, callback, options)](#apidoc.element.cloudinary.uploader.upload_chunked)
- description and source-code
```javascript
upload_chunked = function (path, callback, options) {
  var file_reader, out_stream;
  file_reader = fs.createReadStream(path);
  out_stream = exports.upload_chunked_stream(callback, options);
  return file_reader.pipe(out_stream);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.upload_chunked_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_chunked_stream (callback, options)](#apidoc.element.cloudinary.uploader.upload_chunked_stream)
- description and source-code
```javascript
upload_chunked_stream = function (callback, options) {
  var chunk_size, chunker, params, ref, sent;
  if (options == null) {
    options = {};
  }
  options = _.extend({}, options, {
    stream: true
  });
  options.x_unique_upload_id = utils.random_public_id();
  params = build_upload_params(options);
  chunk_size = (ref = options.chunk_size) != null ? ref : options.part_size;
  chunker = new Chunkable({
    chunk_size: chunk_size
  });
  sent = 0;
  chunker.on('ready', function(buffer, is_last, done) {
    var chunk_start, finished_part, stream;
    chunk_start = sent;
    sent += buffer.length;
    options.content_range = util.format("bytes %d-%d/%d", chunk_start, sent - 1, is_last ? sent : -1);
    finished_part = function(result) {
      if ((result.error != null) || is_last) {
        if (typeof callback === "function") {
          callback(result);
        }
        return done(false);
      } else {
        return done(true);
      }
    };
    stream = call_api("upload", finished_part, options, function() {
      return [params, {}, buffer];
    });
    return stream.write(buffer, 'buffer', function() {
      return stream.end();
    });
  });
  return chunker;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.upload_large"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_large (path, callback, options)](#apidoc.element.cloudinary.uploader.upload_large)
- description and source-code
```javascript
upload_large = function (path, callback, options) {
  if (options == null) {
    options = {};
  }
  return exports.upload_chunked(path, callback, _.extend({
    resource_type: 'raw'
  }, options));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.upload_large_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_large_stream (_unused_, callback, options)](#apidoc.element.cloudinary.uploader.upload_large_stream)
- description and source-code
```javascript
upload_large_stream = function (_unused_, callback, options) {
  if (options == null) {
    options = {};
  }
  return exports.upload_chunked_stream(callback, _.extend({
    resource_type: 'raw'
  }, options));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.upload_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_stream (callback, options)](#apidoc.element.cloudinary.uploader.upload_stream)
- description and source-code
```javascript
upload_stream = function (callback, options) {
  if (options == null) {
    options = {};
  }
  return exports.upload(null, callback, _.extend({
    stream: true
  }, options));
}
```
- example usage
```shell
...
Setting the 'cloud_name', 'api_key' and 'api_secret' parameters can be done either directly in each call to a Cloudinary method,
by calling the cloudinary.config(), or by using the CLOUDINARY_URL environment variable.

### Overriding the request agent
To override the request agent pass the agent into any method that makes a
request and it will be used instead of the normal https agent. e.g
'''js

cloudinary.uploader.upload_stream(
  function(result) { console.log(result); },
  { agent: myAgent }
);

'''

### Embedding and transforming images
...
```

#### <a name="apidoc.element.cloudinary.uploader.upload_tag_params"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_tag_params (options)](#apidoc.element.cloudinary.uploader.upload_tag_params)
- description and source-code
```javascript
upload_tag_params = function (options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = build_upload_params(options);
  params = utils.process_request_params(params, options);
  return JSON.stringify(params);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.uploader.upload_url"></a>[function <span class="apidocSignatureSpan">cloudinary.uploader.</span>upload_url (options)](#apidoc.element.cloudinary.uploader.upload_url)
- description and source-code
```javascript
upload_url = function (options) {
  if (options == null) {
    options = {};
  }
  if (options.resource_type == null) {
    options.resource_type = "auto";
  }
  return utils.api_url("upload", options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.utils"></a>[module cloudinary.utils](#apidoc.module.cloudinary.utils)

#### <a name="apidoc.element.cloudinary.utils.api_sign_request"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>api_sign_request (params_to_sign, api_secret)](#apidoc.element.cloudinary.utils.api_sign_request)
- description and source-code
```javascript
api_sign_request = function (params_to_sign, api_secret) {
  var k, shasum, to_sign, v;
  to_sign = _.sortBy((function() {
    var results;
    results = [];
    for (k in params_to_sign) {
      v = params_to_sign[k];
      if (v != null) {
        results.push(k + "=" + (utils.build_array(v).join(",")));
      }
    }
    return results;
  })(), _.identity).join("&");
  shasum = crypto.createHash('sha1');
  shasum.update(utf8_encode(to_sign + api_secret), 'binary');
  return shasum.digest('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.api_url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>api_url (action, options)](#apidoc.element.cloudinary.utils.api_url)
- description and source-code
```javascript
api_url = function (action, options) {
  var cloud_name, cloudinary, ref, ref1, ref2, ref3, resource_type;
  if (action == null) {
    action = 'upload';
  }
  if (options == null) {
    options = {};
  }
  cloudinary = (ref = (ref1 = options["upload_prefix"]) != null ? ref1 : config().upload_prefix) != null ? ref : "https://api.cloudinary
.com";
  cloud_name = (function() {
    var ref3;
    if ((ref2 = (ref3 = options["cloud_name"]) != null ? ref3 : config().cloud_name) != null) {
      return ref2;
    } else {
      throw "Must supply cloud_name";
    }
  })();
  resource_type = (ref3 = options["resource_type"]) != null ? ref3 : "image";
  return [cloudinary, "v1_1", cloud_name, resource_type, action].join("/");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.archive_params"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>archive_params (options)](#apidoc.element.cloudinary.utils.archive_params)
- description and source-code
```javascript
archive_params = function (options) {
  var ref;
  if (options == null) {
    options = {};
  }
  return {
    async: exports.as_safe_bool(options.async),
    flatten_folders: exports.as_safe_bool(options.flatten_folders),
    flatten_transformations: exports.as_safe_bool(options.flatten_transformations),
    keep_derived: exports.as_safe_bool(options.keep_derived),
    mode: options.mode,
    notification_url: options.notification_url,
    prefixes: options.prefixes && exports.build_array(options.prefixes),
    transformations: utils.build_eager(options.transformations),
    public_ids: options.public_ids && exports.build_array(options.public_ids),
    tags: options.tags && exports.build_array(options.tags),
    target_format: options.target_format,
    target_public_id: options.target_public_id,
    target_tags: options.target_tags && exports.build_array(options.target_tags),
    timestamp: (ref = options.timestamp) != null ? ref : exports.timestamp(),
    transformations: utils.build_eager(options.transformations),
    type: options.type,
    use_original_filename: exports.as_safe_bool(options.use_original_filename)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.as_safe_bool"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>as_safe_bool (value)](#apidoc.element.cloudinary.utils.as_safe_bool)
- description and source-code
```javascript
as_safe_bool = function (value) {
  if (value == null) {
    return void 0;
  }
  if (value === true || value === 'true' || value === '1') {
    value = 1;
  }
  if (value === false || value === 'false' || value === '0') {
    value = 0;
  }
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.build_array"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_array (arg)](#apidoc.element.cloudinary.utils.build_array)
- description and source-code
```javascript
build_array = function (arg) {
  if (arg == null) {
    return [];
  } else if (_.isArray(arg)) {
    return arg;
  } else {
    return [arg];
  }
}
```
- example usage
```shell
...

html = '<video ';

if (!video_options.hasOwnProperty('resource_type')) video_options.resource_type = 'video';
multi_source = _.isArray(source_types) && source_types.length > 1;
source = public_id;
if (!multi_source) {
  source = source + '.' + cloudinary.utils.build_array(source_types)[0];
}
src = cloudinary.utils.url(source, video_options);
if (!multi_source) video_options.src = src;
if (video_options.hasOwnProperty("html_width")) video_options.width = cloudinary.utils.option_consume(video_options, 'html_width
');
if (video_options.hasOwnProperty("html_height")) video_options.height = cloudinary.utils.option_consume(video_options, 'html_height
');
html = html + cloudinary.utils.html_attrs(video_options) + '>';
if (multi_source) {
...
```

#### <a name="apidoc.element.cloudinary.utils.build_custom_headers"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_custom_headers (headers)](#apidoc.element.cloudinary.utils.build_custom_headers)
- description and source-code
```javascript
build_custom_headers = function (headers) {
  var k, v;
  switch (false) {
    case !(headers == null):
      return void 0;
    case !_.isArray(headers):
      return headers.join("\n");
    case !_.isObject(headers):
      return [
        (function() {
          var results;
          results = [];
          for (k in headers) {
            v = headers[k];
            results.push(k + ": " + v);
          }
          return results;
        })()
      ].join("\n");
    default:
      return headers;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.build_eager"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_eager (transformations)](#apidoc.element.cloudinary.utils.build_eager)
- description and source-code
```javascript
build_eager = function (transformations) {
  var transformation;
  return ((function() {
    var j, len, ref, results;
    ref = utils.build_array(transformations);
    results = [];
    for (j = 0, len = ref.length; j < len; j++) {
      transformation = ref[j];
      transformation = _.clone(transformation);
      results.push(_.filter([utils.generate_transformation_string(transformation), transformation.format], utils.present).join("/"));
    }
    return results;
  })()).join("|");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.build_explicit_api_params"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_explicit_api_params (public_id, options)](#apidoc.element.cloudinary.utils.build_explicit_api_params)
- description and source-code
```javascript
build_explicit_api_params = function (public_id, options) {
  var opt;
  if (options == null) {
    options = {};
  }
  opt = [
    {
      callback: options.callback,
      colors: utils.as_safe_bool(options.colors),
      custom_coordinates: options.custom_coordinates && utils.encode_double_array(options.custom_coordinates),
      eager: utils.build_eager(options.eager),
      eager_async: utils.as_safe_bool(options.eager_async),
      eager_notification_url: options.eager_notification_url,
      face_coordinates: options.face_coordinates && utils.encode_double_array(options.face_coordinates),
      headers: build_custom_headers(options.headers),
      image_metadata: utils.as_safe_bool(options.image_metadata),
      invalidate: utils.as_safe_bool(options.invalidate),
      moderation: options.moderation,
      phash: utils.as_safe_bool(options.phash),
      public_id: public_id,
      responsive_breakpoints: utils.generate_responsive_breakpoints_string(options.responsive_breakpoints),
      tags: options.tags && utils.build_array(options.tags).join(","),
      timestamp: options.timestamp || exports.timestamp(),
      type: options.type
    }
  ];
  return opt;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.build_streaming_profiles_param"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_streaming_profiles_param (options)](#apidoc.element.cloudinary.utils.build_streaming_profiles_param)
- description and source-code
```javascript
build_streaming_profiles_param = function (options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = utils.only(options, "display_name", "representations");
  if (_.isArray(params["representations"])) {
    params["representations"] = JSON.stringify(params["representations"].map(function(r) {
      return {
        transformation: utils.generate_transformation_string(r.transformation)
      };
    }));
  }
  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.build_upload_params"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>build_upload_params (options)](#apidoc.element.cloudinary.utils.build_upload_params)
- description and source-code
```javascript
build_upload_params = function (options) {
  var params;
  params = {
    access_mode: options.access_mode,
    allowed_formats: options.allowed_formats && utils.build_array(options.allowed_formats).join(","),
    backup: utils.as_safe_bool(options.backup),
    callback: options.callback,
    colors: utils.as_safe_bool(options.colors),
    discard_original_filename: utils.as_safe_bool(options.discard_original_filename),
    eager: utils.build_eager(options.eager),
    eager_async: utils.as_safe_bool(options.eager_async),
    eager_notification_url: options.eager_notification_url,
    exif: utils.as_safe_bool(options.exif),
    faces: utils.as_safe_bool(options.faces),
    folder: options.folder,
    format: options.format,
    image_metadata: utils.as_safe_bool(options.image_metadata),
    invalidate: utils.as_safe_bool(options.invalidate),
    moderation: options.moderation,
    notification_url: options.notification_url,
    overwrite: utils.as_safe_bool(options.overwrite),
    phash: utils.as_safe_bool(options.phash),
    proxy: options.proxy,
    public_id: options.public_id,
    responsive_breakpoints: utils.generate_responsive_breakpoints_string(options["responsive_breakpoints"]),
    return_delete_token: utils.as_safe_bool(options.return_delete_token),
    timestamp: exports.timestamp(),
    transformation: utils.generate_transformation_string(_.clone(options)),
    type: options.type,
    unique_filename: utils.as_safe_bool(options.unique_filename),
    upload_preset: options.upload_preset,
    use_filename: utils.as_safe_bool(options.use_filename)
  };
  return utils.updateable_resource_params(options, params);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.clear_blank"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>clear_blank (hash)](#apidoc.element.cloudinary.utils.clear_blank)
- description and source-code
```javascript
clear_blank = function (hash) {
  var filtered_hash, k, v;
  filtered_hash = {};
  for (k in hash) {
    v = hash[k];
    if (exports.present(v)) {
      filtered_hash[k] = hash[k];
    }
  }
  return filtered_hash;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.cloudinary_js_config"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>cloudinary_js_config ()](#apidoc.element.cloudinary.utils.cloudinary_js_config)
- description and source-code
```javascript
cloudinary_js_config = function () {
  var j, len, param, params, value;
  params = {};
  for (j = 0, len = CLOUDINARY_JS_CONFIG_PARAMS.length; j < len; j++) {
    param = CLOUDINARY_JS_CONFIG_PARAMS[j];
    value = config()[param];
    if (value != null) {
      params[param] = value;
    }
  }
  return "<script type='text/javascript'>\n" + "$.cloudinary.config(" + JSON.stringify(params) + ");\n" + "</script>\n";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.download_archive_url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>download_archive_url (options)](#apidoc.element.cloudinary.utils.download_archive_url)
- description and source-code
```javascript
download_archive_url = function (options) {
  var cloudinary_params;
  if (options == null) {
    options = {};
  }
  cloudinary_params = exports.sign_request(exports.archive_params(_.merge(options, {
    mode: "download"
  })), options);
  return exports.api_url("generate_archive", options) + "?" + hashToQuery(cloudinary_params);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.download_zip_url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>download_zip_url (options)](#apidoc.element.cloudinary.utils.download_zip_url)
- description and source-code
```javascript
download_zip_url = function (options) {
  if (options == null) {
    options = {};
  }
  return exports.download_archive_url(_.merge(options, {
    target_format: "zip"
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.encode_double_array"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>encode_double_array (array)](#apidoc.element.cloudinary.utils.encode_double_array)
- description and source-code
```javascript
encode_double_array = function (array) {
  array = utils.build_array(array);
  if (array.length > 0 && _.isArray(array[0])) {
    return array.map(function(e) {
      return utils.build_array(e).join(",");
    }).join("|");
  } else {
    return array.join(",");
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.encode_key_value"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>encode_key_value (arg)](#apidoc.element.cloudinary.utils.encode_key_value)
- description and source-code
```javascript
encode_key_value = function (arg) {
  var k, pairs, v;
  if (_.isObject(arg)) {
    pairs = (function() {
      var results;
      results = [];
      for (k in arg) {
        v = arg[k];
        results.push(k + "=" + v);
      }
      return results;
    })();
    return pairs.join("|");
  } else {
    return arg;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.generate_auth_token"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>generate_auth_token (options)](#apidoc.element.cloudinary.utils.generate_auth_token)
- description and source-code
```javascript
generate_auth_token = function (options) {
  var token_options;
  token_options = Object.assign({}, config().auth_token, options);
  return generate_token(token_options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.generate_responsive_breakpoints_string"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>generate_responsive_breakpoints_string (breakpoints)](#apidoc.element.cloudinary.utils.generate_responsive_breakpoints_string)
- description and source-code
```javascript
generate_responsive_breakpoints_string = function (breakpoints) {
  var breakpoint_settings, j, len, transformation;
  if (breakpoints == null) {
    return;
  }
  breakpoints = _.clone(breakpoints);
  if (!_.isArray(breakpoints)) {
    breakpoints = [breakpoints];
  }
  for (j = 0, len = breakpoints.length; j < len; j++) {
    breakpoint_settings = breakpoints[j];
    if (breakpoint_settings != null) {
      transformation = breakpoint_settings.transformation;
      delete breakpoint_settings.transformation;
      if (transformation) {
        breakpoint_settings.transformation = utils.generate_transformation_string(_.clone(transformation));
      }
    }
  }
  return JSON.stringify(breakpoints);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.generate_transformation_string"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>generate_transformation_string (options)](#apidoc.element.cloudinary.utils.generate_transformation_string)
- description and source-code
```javascript
generate_transformation_string = function (options) {
  var angle, background, base_transformation, base_transformations, border, color, crop, dpr, effect, flags, has_layer, height,
ifValue, j, key, keys, l, len, len1, name, named_transformation, no_html_sizes, overlay, param, params, range_value, raw_transformation
, ref, ref1, ref2, ref3, ref4, ref5, ref6, responsive_width, responsive_width_transformation, result, short, simple_params, size
, sortedParams, transformations, underlay, value, var_params, variables, width;
  if (_.isArray(options)) {
    result = (function() {
      var j, len, results;
      results = [];
      for (j = 0, len = options.length; j < len; j++) {
        base_transformation = options[j];
        results.push(utils.generate_transformation_string(_.clone(base_transformation)));
      }
      return results;
    })();
    return result.join("/");
  }
  responsive_width = utils.option_consume(options, "responsive_width", config().responsive_width);
  width = options["width"];
  height = options["height"];
  size = utils.option_consume(options, "size");
  if (size) {
    ref1 = (ref = size.split("x"), width = ref[0], height = ref[1], ref), options["width"] = ref1[0], options["height"] = ref1[1
];
  }
  has_layer = options.overlay || options.underlay;
  crop = utils.option_consume(options, "crop");
  angle = utils.build_array(utils.option_consume(options, "angle")).join(".");
  no_html_sizes = has_layer || utils.present(angle) || crop === "fit" || crop === "limit" || responsive_width;
  if (width && (width.toString().indexOf("auto") === 0 || no_html_sizes || parseFloat(width) < 1)) {
    delete options["width"];
  }
  if (height && (no_html_sizes || parseFloat(height) < 1)) {
    delete options["height"];
  }
  background = utils.option_consume(options, "background");
  background = background && background.replace(/^#/, "rgb:");
  color = utils.option_consume(options, "color");
  color = color && color.replace(/^#/, "rgb:");
  base_transformations = utils.build_array(utils.option_consume(options, "transformation", []));
  named_transformation = [];
  if (base_transformations.length !== 0 && _.filter(base_transformations, _.isObject).length > 0) {
    base_transformations = _.map(base_transformations, function(base_transformation) {
      if (_.isObject(base_transformation)) {
        return utils.generate_transformation_string(_.clone(base_transformation));
      } else {
        return utils.generate_transformation_string({
          transformation: base_transformation
        });
      }
    });
  } else {
    named_transformation = base_transformations.join(".");
    base_transformations = [];
  }
  effect = utils.option_consume(options, "effect");
  if (_.isArray(effect)) {
    effect = effect.join(":");
  } else if (_.isObject(effect)) {
    for (key in effect) {
      value = effect[key];
      effect = key + ":" + value;
    }
  }
  border = utils.option_consume(options, "border");
  if (_.isObject(border)) {
    border = ((ref2 = border.width) != null ? ref2 : 2) + "px_solid_" + (((ref3 = border.color) != null ? ref3 : "black").replace
(/^#/, 'rgb:'));
  } else if (/^\d+$/.exec(border)) {
    options.border = border;
    border = void 0;
  }
  flags = utils.build_array(utils.option_consume(options, "flags")).join(".");
  dpr = utils.option_consume(options, "dpr", config().dpr);
  if (options["offset"] != null) {
    ref4 = split_range(utils.option_consume(options, "offset")), options["start_offset"] = ref4[0], options["end_offset"] = ref4
[1];
  }
  overlay = process_layer(utils.option_consume(options, "overlay"));
  underlay = process_layer(utils.option_consume(options, "underlay"));
  ifValue = process_if(utils.option_consume(options, "if"));
  params = {
    a: normalize_expression(angle),
    ar: normalize_expression(utils.option_consume(options, "aspect_ratio")),
    b: background,
    bo: border,
    c: crop,
    co: color,
    dpr: normalize_expression(dpr),
    e: normalize_expression(effect),
    fl: flags,
    h: normalize_expression(height),
    l: overlay,
    o: normalize_expression(utils.option_consume(opt ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.getUserAgent"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>getUserAgent ()](#apidoc.element.cloudinary.utils.getUserAgent)
- description and source-code
```javascript
getUserAgent = function () {
  if (_.isEmpty(utils.userPlatform)) {
    return "" + utils.USER_AGENT;
  } else {
    return utils.userPlatform + " " + utils.USER_AGENT;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.html_attrs"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>html_attrs (attrs)](#apidoc.element.cloudinary.utils.html_attrs)
- description and source-code
```javascript
html_attrs = function (attrs) {
  var pairs;
  pairs = _.filter(_.map(attrs, function(value, key) {
    return join_pair(key, value);
  }));
  pairs.sort();
  return pairs.join(" ");
}
```
- example usage
```shell
...
   source = cloudinary.utils.option_consume(options, "responsive_placeholder", cloudinary.config().responsive_placeholder);
   if (source == "blank") {
     source = cloudinary.BLANK;
   }
 }
 html = "<img ";
 if (source) html += "src='" + source + "' ";
 html += cloudinary.utils.html_attrs(options) + "/>";
 return html;
};

/**
* Creates an HTML video tag for the provided public_id
* @param {String} public_id the resource public ID
* @param {Object} [options] options for the resource and HTML tag
...
```

#### <a name="apidoc.element.cloudinary.utils.merge"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>merge (hash1, hash2)](#apidoc.element.cloudinary.utils.merge)
- description and source-code
```javascript
merge = function (hash1, hash2) {
  var k, result, v;
  result = {};
  for (k in hash1) {
    v = hash1[k];
    result[k] = hash1[k];
  }
  for (k in hash2) {
    v = hash2[k];
    result[k] = hash2[k];
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.only"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>only ()](#apidoc.element.cloudinary.utils.only)
- description and source-code
```javascript
only = function () {
  var hash, j, key, keys, len, result;
  hash = arguments[0], keys = 2 <= arguments.length ? slice.call(arguments, 1) : [];
  result = {};
  for (j = 0, len = keys.length; j < len; j++) {
    key = keys[j];
    if (hash[key] != null) {
      result[key] = hash[key];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.option_consume"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>option_consume (options, option_name, default_value)](#apidoc.element.cloudinary.utils.option_consume)
- description and source-code
```javascript
option_consume = function (options, option_name, default_value) {
  var result;
  result = options[option_name];
  delete options[option_name];
  if (result != null) {
    return result;
  } else {
    return default_value;
  }
}
```
- example usage
```shell
...
return cloudinary.utils.url(public_id, options);
};

exports.image = function (source, options) {
var responsive, html, current_class, classes;
options = _.extend({}, options);
source = cloudinary.utils.url(source, options);
if ("html_width" in options) options["width"] = cloudinary.utils.option_consume(options, "html_width");
if ("html_height" in options) options["height"] = cloudinary.utils.option_consume(options, "html_height");

client_hints = cloudinary.utils.option_consume(options, "client_hints", cloudinary.config().client_hints);
responsive = cloudinary.utils.option_consume(options, "responsive");
hidpi = cloudinary.utils.option_consume(options, "hidpi");

if ((responsive || hidpi) && !client_hints) {
...
```

#### <a name="apidoc.element.cloudinary.utils.present"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>present (value)](#apidoc.element.cloudinary.utils.present)
- description and source-code
```javascript
present = function (value) {
  return !_.isUndefined(value) && ("" + value).length > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.private_download_url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>private_download_url (public_id, format, options)](#apidoc.element.cloudinary.utils.private_download_url)
- description and source-code
```javascript
private_download_url = function (public_id, format, options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = exports.sign_request({
    timestamp: exports.timestamp(),
    public_id: public_id,
    format: format,
    type: options.type,
    attachment: options.attachment,
    expires_at: options.expires_at
  }, options);
  return exports.api_url("download", options) + "?" + querystring.stringify(params);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.process_request_params"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>process_request_params (params, options)](#apidoc.element.cloudinary.utils.process_request_params)
- description and source-code
```javascript
process_request_params = function (params, options) {
  if ((options.unsigned != null) && options.unsigned) {
    params = exports.clear_blank(params);
    delete params["timestamp"];
  } else {
    params = exports.sign_request(params, options);
  }
  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.random_public_id"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>random_public_id ()](#apidoc.element.cloudinary.utils.random_public_id)
- description and source-code
```javascript
random_public_id = function () {
  return crypto.randomBytes(12).toString('base64').replace(/[^a-z0-9]/g, "");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.sign_request"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>sign_request (params, options)](#apidoc.element.cloudinary.utils.sign_request)
- description and source-code
```javascript
sign_request = function (params, options) {
  var api_key, api_secret, ref, ref1;
  if (options == null) {
    options = {};
  }
  api_key = (function() {
    var ref1;
    if ((ref = (ref1 = options.api_key) != null ? ref1 : config().api_key) != null) {
      return ref;
    } else {
      throw "Must supply api_key";
    }
  })();
  api_secret = (function() {
    var ref2;
    if ((ref1 = (ref2 = options.api_secret) != null ? ref2 : config().api_secret) != null) {
      return ref1;
    } else {
      throw "Must supply api_secret";
    }
  })();
  params = exports.clear_blank(params);
  params.signature = exports.api_sign_request(params, api_secret);
  params.api_key = api_key;
  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.signed_preloaded_image"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>signed_preloaded_image (result)](#apidoc.element.cloudinary.utils.signed_preloaded_image)
- description and source-code
```javascript
signed_preloaded_image = function (result) {
  return result.resource_type + "/upload/v" + result.version + "/" + (_.filter([result.public_id, result.format], utils.present).
join(".")) + "#" + result.signature;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.timestamp"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>timestamp ()](#apidoc.element.cloudinary.utils.timestamp)
- description and source-code
```javascript
timestamp = function () {
  return Math.floor(new Date().getTime() / 1000);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.updateable_resource_params"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>updateable_resource_params (options, params)](#apidoc.element.cloudinary.utils.updateable_resource_params)
- description and source-code
```javascript
updateable_resource_params = function (options, params) {
  if (params == null) {
    params = {};
  }
  if (options.auto_tagging != null) {
    params.auto_tagging = options.auto_tagging;
  }
  if (options.background_removal != null) {
    params.background_removal = options.background_removal;
  }
  if (options.categorization != null) {
    params.categorization = options.categorization;
  }
  if (options.context != null) {
    params.context = utils.encode_key_value(options.context);
  }
  if (options.custom_coordinates != null) {
    params.custom_coordinates = utils.encode_double_array(options.custom_coordinates);
  }
  if (options.detection != null) {
    params.detection = options.detection;
  }
  if (options.face_coordinates != null) {
    params.face_coordinates = utils.encode_double_array(options.face_coordinates);
  }
  if (options.headers != null) {
    params.headers = utils.build_custom_headers(options.headers);
  }
  if (options.ocr != null) {
    params.ocr = options.ocr;
  }
  if (options.raw_convert != null) {
    params.raw_convert = options.raw_convert;
  }
  if (options.similarity_search != null) {
    params.similarity_search = options.similarity_search;
  }
  if (options.tags != null) {
    params.tags = utils.build_array(options.tags).join(",");
  }
  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>url (public_id, options)](#apidoc.element.cloudinary.utils.url)
- description and source-code
```javascript
url = function (public_id, options) {
  var api_secret, auth_token, cdn_subdomain, cloud_name, cname, format, original_source, prefix, preloaded, private_cdn, ref, ref1
, resource_type, resultUrl, secure, secure_cdn_subdomain, secure_distribution, shasum, shorten, sign_url, signature, source_to_sign
, ssl_detected, to_sign, token, transformation, type, url_suffix, use_root_path, version;
  if (options == null) {
    options = {};
  }
  type = utils.option_consume(options, "type", null);
  if (type === "fetch") {
    if (options.fetch_format == null) {
      options.fetch_format = utils.option_consume(options, "format");
    }
  }
  transformation = utils.generate_transformation_string(options);
  resource_type = utils.option_consume(options, "resource_type", "image");
  version = utils.option_consume(options, "version");
  format = utils.option_consume(options, "format");
  cloud_name = utils.option_consume(options, "cloud_name", config().cloud_name);
  if (!cloud_name) {
    throw "Unknown cloud_name";
  }
  private_cdn = utils.option_consume(options, "private_cdn", config().private_cdn);
  secure_distribution = utils.option_consume(options, "secure_distribution", config().secure_distribution);
  secure = utils.option_consume(options, "secure", null);
  ssl_detected = utils.option_consume(options, "ssl_detected", config().ssl_detected);
  if (secure === null) {
    secure = ssl_detected || config().secure;
  }
  cdn_subdomain = utils.option_consume(options, "cdn_subdomain", config().cdn_subdomain);
  secure_cdn_subdomain = utils.option_consume(options, "secure_cdn_subdomain", config().secure_cdn_subdomain);
  cname = utils.option_consume(options, "cname", config().cname);
  shorten = utils.option_consume(options, "shorten", config().shorten);
  sign_url = utils.option_consume(options, "sign_url", config().sign_url);
  api_secret = utils.option_consume(options, "api_secret", config().api_secret);
  url_suffix = utils.option_consume(options, "url_suffix");
  use_root_path = utils.option_consume(options, "use_root_path", config().use_root_path);
  auth_token = utils.option_consume(options, "auth_token");
  if (auth_token !== false) {
    auth_token = exports.merge(config().auth_token, auth_token);
  }
  preloaded = /^(image|raw)\/([a-z0-9_]+)\/v(\d+)\/([^#]+)$/.exec(public_id);
  if (preloaded) {
    resource_type = preloaded[1];
    type = preloaded[2];
    version = preloaded[3];
    public_id = preloaded[4];
  }
  if (url_suffix && !private_cdn) {
    throw 'URL Suffix only supported in private CDN';
  }
  original_source = public_id;
  if (public_id == null) {
    return original_source;
  }
  public_id = public_id.toString();
  if (type === null && public_id.match(/^https?:\//i)) {
    return original_source;
  }
  ref = finalize_resource_type(resource_type, type, url_suffix, use_root_path, shorten), resource_type = ref[0], type = ref[1];
  ref1 = finalize_source(public_id, format, url_suffix), public_id = ref1[0], source_to_sign = ref1[1];
  if (source_to_sign.indexOf("/") > 0 && !source_to_sign.match(/^v[0-9]+/) && !source_to_sign.match(/^https?:\//)) {
    if (version == null) {
      version = 1;
    }
  }
  if (version != null) {
    version = "v" + version;
  }
  transformation = transformation.replace(/([^:])\/\//g, '$1/');
  if (sign_url && _.isEmpty(auth_token)) {
    to_sign = [transformation, source_to_sign].filter(function(part) {
      return (part != null) && part !== '';
    }).join('/');
    shasum = crypto.createHash('sha1');
    shasum.update(utf8_encode(to_sign + api_secret), 'binary');
    signature = shasum.digest('base64').replace(/\//g, '_').replace(/\+/g, '-').substring(0, 8);
    signature = "s--" + signature + "--";
  }
  prefix = unsigned_url_prefix(public_id, cloud_name, private_cdn, cdn_subdomain, secure_cdn_subdomain, cname, secure, secure_distribution
);
  resultUrl = [prefix, resource_type, type, signature, transformation, version, public_id].filter(function(part) {
    return (part != null) && part !== '';
  }).join('/');
  if (sign_url && !_.isEmpty(auth_token)) {
    auth_token.url = url.p ...
```
- example usage
```shell
...

### Embedding and transforming images

Any image uploaded to Cloudinary can be transformed and embedded using powerful view helper methods:

The following example generates the url for accessing an uploaded 'sample' image while transforming it to fill a 100x150 rectangle
:

    cloudinary.url("sample.jpg", {width: 100, height: 150, crop: "fill"})

Another example, emedding a smaller version of an uploaded image while generating a 90x90 face detection based thumbnail:

    cloudinary.url("woman.jpg", {width: 90, height: 90, crop: "thumb", gravity: "face"})

You can provide either a Facebook name or a numeric ID of a Facebook profile or a fan page.
...
```

#### <a name="apidoc.element.cloudinary.utils.v1_adapters"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>v1_adapters (exports, v1, mapping)](#apidoc.element.cloudinary.utils.v1_adapters)
- description and source-code
```javascript
v1_adapters = function (exports, v1, mapping) {
  var name, num_pass_args, results;
  results = [];
  for (name in mapping) {
    num_pass_args = mapping[name];
    results.push(exports[name] = v1_adapter(name, num_pass_args, v1));
  }
  return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.video_thumbnail_url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>video_thumbnail_url (public_id, options)](#apidoc.element.cloudinary.utils.video_thumbnail_url)
- description and source-code
```javascript
video_thumbnail_url = function (public_id, options) {
  options = _.extend({}, exports.DEFAULT_POSTER_OPTIONS, options);
  return utils.url(public_id, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.video_url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>video_url (public_id, options)](#apidoc.element.cloudinary.utils.video_url)
- description and source-code
```javascript
video_url = function (public_id, options) {
  options = _.extend({
    resource_type: 'video'
  }, options);
  return utils.url(public_id, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.webhook_signature"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>webhook_signature (data, timestamp, options)](#apidoc.element.cloudinary.utils.webhook_signature)
- description and source-code
```javascript
webhook_signature = function (data, timestamp, options) {
  var api_secret, ref, shasum;
  if (options == null) {
    options = {};
  }
  if (!data) {
    throw "Must supply data";
  }
  if (!timestamp) {
    throw "Must supply timestamp";
  }
  api_secret = (function() {
    var ref1;
    if ((ref = (ref1 = options.api_secret) != null ? ref1 : config().api_secret) != null) {
      return ref;
    } else {
      throw "Must supply api_secret";
    }
  })();
  shasum = crypto.createHash('sha1');
  shasum.update(data + timestamp + api_secret, 'binary');
  return shasum.digest('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.utils.zip_download_url"></a>[function <span class="apidocSignatureSpan">cloudinary.utils.</span>zip_download_url (tag, options)](#apidoc.element.cloudinary.utils.zip_download_url)
- description and source-code
```javascript
zip_download_url = function (tag, options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = exports.sign_request({
    timestamp: exports.timestamp(),
    tag: tag,
    transformation: utils.generate_transformation_string(options)
  }, options);
  return exports.api_url("download_tag.zip", options) + "?" + hashToQuery(params);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.v2"></a>[module cloudinary.v2](#apidoc.module.cloudinary.v2)

#### <a name="apidoc.element.cloudinary.v2.PreloadedFile"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.</span>PreloadedFile (file_info)](#apidoc.element.cloudinary.v2.PreloadedFile)
- description and source-code
```javascript
function PreloadedFile(file_info) {
  var matches, public_id_and_format;
  matches = file_info.match(PRELOADED_CLOUDINARY_PATH);
  if (!matches) {
    throw "Invalid preloaded file info";
  }
  this.resource_type = matches[1];
  this.type = matches[2];
  this.version = matches[3];
  this.filename = matches[4];
  this.signature = matches[5];
  public_id_and_format = this.split_format(this.filename);
  this.public_id = public_id_and_format[0];
  this.format = public_id_and_format[1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.cloudinary_js_config"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.</span>cloudinary_js_config ()](#apidoc.element.cloudinary.v2.cloudinary_js_config)
- description and source-code
```javascript
cloudinary_js_config = function () {
  var j, len, param, params, value;
  params = {};
  for (j = 0, len = CLOUDINARY_JS_CONFIG_PARAMS.length; j < len; j++) {
    param = CLOUDINARY_JS_CONFIG_PARAMS[j];
    value = config()[param];
    if (value != null) {
      params[param] = value;
    }
  }
  return "<script type='text/javascript'>\n" + "$.cloudinary.config(" + JSON.stringify(params) + ");\n" + "</script>\n";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.config"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.</span>config (new_config, new_value)](#apidoc.element.cloudinary.v2.config)
- description and source-code
```javascript
config = function (new_config, new_value) {
  var cloudinary_url, k, ref, uri, v;
  if ((cloudinary_config == null) || new_config === true) {
    cloudinary_url = process.env.CLOUDINARY_URL;
    if (cloudinary_url != null) {
      uri = require('url').parse(cloudinary_url, true);
      cloudinary_config = {
        cloud_name: uri.host,
        api_key: uri.auth && uri.auth.split(":")[0],
        api_secret: uri.auth && uri.auth.split(":")[1],
        private_cdn: uri.pathname != null,
        secure_distribution: uri.pathname && uri.pathname.substring(1)
      };
      if (uri.query != null) {
        ref = uri.query;
        for (k in ref) {
          v = ref[k];
          if (isNestedKey(k)) {
            putNestedValue(cloudinary_config, k, v);
          } else {
            cloudinary_config[k] = v;
          }
        }
      }
    } else {
      cloudinary_config = {};
    }
  }
  if (!_.isUndefined(new_value)) {
    cloudinary_config[new_config] = new_value;
  } else if (_.isString(new_config)) {
    return cloudinary_config[new_config];
  } else if (_.isObject(new_config)) {
    _.extend(cloudinary_config, new_config);
  }
  return cloudinary_config;
}
```
- example usage
```shell
...
## Usage

### Configuration

Each request for building a URL of a remote cloud resource must have the 'cloud_name' parameter set.
Each request to our secure APIs (e.g., image uploads, eager sprite generation) must have the 'api_key' and 'api_secret' parameters
 set. See [API, URLs and access identifiers](http://cloudinary.com/documentation/api_and_access_identifiers) for more details.

Setting the 'cloud_name', 'api_key' and 'api_secret' parameters can be done either directly in each call to a Cloudinary method,
by calling the cloudinary.config(), or by using the CLOUDINARY_URL environment variable.

### Overriding the request agent
To override the request agent pass the agent into any method that makes a
request and it will be used instead of the normal https agent. e.g
'''js

cloudinary.uploader.upload_stream(
...
```

#### <a name="apidoc.element.cloudinary.v2.image"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.</span>image (source, options)](#apidoc.element.cloudinary.v2.image)
- description and source-code
```javascript
image = function (source, options) {
  var responsive, html, current_class, classes;
  options = _.extend({}, options);
  source = cloudinary.utils.url(source, options);
  if ("html_width" in options) options["width"] = cloudinary.utils.option_consume(options, "html_width");
  if ("html_height" in options) options["height"] = cloudinary.utils.option_consume(options, "html_height");

  client_hints = cloudinary.utils.option_consume(options, "client_hints", cloudinary.config().client_hints);
  responsive = cloudinary.utils.option_consume(options, "responsive");
  hidpi = cloudinary.utils.option_consume(options, "hidpi");

  if ((responsive || hidpi) && !client_hints) {
    options["data-src"] = source;
    classes = [responsive ? "cld-responsive" : "cld-hidpi"];
    current_class = cloudinary.utils.option_consume(options, "class");
    if (current_class) classes.push(current_class);
    options["class"] = classes.join(" ");
    source = cloudinary.utils.option_consume(options, "responsive_placeholder", cloudinary.config().responsive_placeholder);
    if (source == "blank") {
      source = cloudinary.BLANK;
    }
  }
  html = "<img ";
  if (source) html += "src='" + source + "' ";
  html += cloudinary.utils.html_attrs(options) + "/>";
  return html;
}
```
- example usage
```shell
...

### cloudinary.image

Returns an html image tag pointing to Cloudinary.

Usage:

    cloudinary.image("sample", {format: "png", width: 100, height: 100, crop: "fill"})

    // <img src='http://res.cloudinary.com/demo/image/upload/c_fill,h_100,w_100/sample.png' height='100' width='100'/>

### Samples

You can find our simple and ready-to-use samples projects, along with documentation in the [samples folder](https://github.com/cloudinary
/cloudinary_npm/tree/master/samples).
Please consult with the [README file](https://github.com/cloudinary/cloudinary_npm/blob/master/samples/README.md), for usage and
 explanations.
...
```

#### <a name="apidoc.element.cloudinary.v2.url"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.</span>url (public_id, options)](#apidoc.element.cloudinary.v2.url)
- description and source-code
```javascript
url = function (public_id, options) {
  options = _.extend({}, options);
  return cloudinary.utils.url(public_id, options);
}
```
- example usage
```shell
...

### Embedding and transforming images

Any image uploaded to Cloudinary can be transformed and embedded using powerful view helper methods:

The following example generates the url for accessing an uploaded 'sample' image while transforming it to fill a 100x150 rectangle
:

    cloudinary.url("sample.jpg", {width: 100, height: 150, crop: "fill"})

Another example, emedding a smaller version of an uploaded image while generating a 90x90 face detection based thumbnail:

    cloudinary.url("woman.jpg", {width: 90, height: 90, crop: "thumb", gravity: "face"})

You can provide either a Facebook name or a numeric ID of a Facebook profile or a fan page.
...
```

#### <a name="apidoc.element.cloudinary.v2.video"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.</span>video (public_id, options)](#apidoc.element.cloudinary.v2.video)
- description and source-code
```javascript
video = function (public_id, options) {
  var src, video_options, fallback, source_transformation, source_types, source, multi_source, html;
  options = _.extend({}, options);
  public_id = public_id.replace(/\.(mp4|ogv|webm)$/, '');
  source_types = cloudinary.utils.option_consume(options, 'source_types', []);
  source_transformation = cloudinary.utils.option_consume(options, 'source_transformation', {});
  fallback = cloudinary.utils.option_consume(options, 'fallback_content', '');

  if (source_types.length === 0) source_types = cloudinary.utils.DEFAULT_VIDEO_SOURCE_TYPES;
  video_options = _.cloneDeep(options);

  if (video_options.hasOwnProperty('poster')) {
    if (_.isPlainObject(video_options.poster)) {
      if (video_options.poster.hasOwnProperty('public_id')) {
        video_options.poster = cloudinary.utils.url(video_options.poster.public_id, video_options.poster);
      } else {
        video_options.poster = cloudinary.utils.url(public_id, _.extend({}, cloudinary.utils.DEFAULT_POSTER_OPTIONS, video_options
.poster));
      }
    }
  } else {
    video_options.poster = cloudinary.utils.url(public_id, _.extend({}, cloudinary.utils.DEFAULT_POSTER_OPTIONS, options));
  }

  if (!video_options.poster) delete video_options.poster;

  html = '<video ';

  if (!video_options.hasOwnProperty('resource_type')) video_options.resource_type = 'video';
  multi_source = _.isArray(source_types) && source_types.length > 1;
  source = public_id;
  if (!multi_source) {
    source = source + '.' + cloudinary.utils.build_array(source_types)[0];
  }
  src = cloudinary.utils.url(source, video_options);
  if (!multi_source) video_options.src = src;
  if (video_options.hasOwnProperty("html_width")) video_options.width = cloudinary.utils.option_consume(video_options, 'html_width
');
  if (video_options.hasOwnProperty("html_height")) video_options.height = cloudinary.utils.option_consume(video_options, 'html_height
');
  html = html + cloudinary.utils.html_attrs(video_options) + '>';
  if (multi_source) {
    var source_type, transformation, video_type, mime_type;
    for (var i = 0; i < source_types.length; i++) {
      source_type = source_types[i];
      transformation = source_transformation[source_type] || {};
      src = cloudinary.utils.url(source + "." + source_type, _.extend({resource_type: 'video'}, _.cloneDeep(options), _.cloneDeep
(transformation)));
      video_type = source_type === 'ogv' ? 'ogg' : source_type;
      mime_type = "video/" + video_type;
      html = html + '<source ' + cloudinary.utils.html_attrs({
        src: src,
        type: mime_type
      }) + '>';
    }
  }

  html = html + fallback;
  html = html + '</video>';
  return html;
}
```
- example usage
```shell
...
 *        source type the tag should include. defaults to webm, mp4 and ogv.
 * @param {String} [options.source_transformation] specific transformations
 *        to use for a specific source type.
 * @param {(String|Object)} [options.poster] image URL or
 *        poster options that may include a <tt>public_id</tt> key and
 *        poster-specific transformations
 * @example <caption>Example of generating a video tag:</caption>
 * $.cloudinary.video("mymovie.mp4");
 * $.cloudinary.video("mymovie.mp4", {source_types: 'webm'});
 * $.cloudinary.video("mymovie.ogv", {poster: "myspecialplaceholder.jpg"});
 * $.cloudinary.video("mymovie.webm", {source_types: ['webm', 'mp4'], poster: {effect: 'sepia'}});
 * @return {string} HTML video tag
 */
exports.video = function (public_id, options) {
var src, video_options, fallback, source_transformation, source_types, source, multi_source, html;
...
```



# <a name="apidoc.module.cloudinary.v2.api"></a>[module cloudinary.v2.api](#apidoc.module.cloudinary.v2.api)

#### <a name="apidoc.element.cloudinary.v2.api.create_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_streaming_profile ()](#apidoc.element.cloudinary.v2.api.create_streaming_profile)
- description and source-code
```javascript
create_streaming_profile = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.create_transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_transformation ()](#apidoc.element.cloudinary.v2.api.create_transformation)
- description and source-code
```javascript
create_transformation = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.create_upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_upload_mapping ()](#apidoc.element.cloudinary.v2.api.create_upload_mapping)
- description and source-code
```javascript
create_upload_mapping = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.create_upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>create_upload_preset ()](#apidoc.element.cloudinary.v2.api.create_upload_preset)
- description and source-code
```javascript
create_upload_preset = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_all_resources"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_all_resources ()](#apidoc.element.cloudinary.v2.api.delete_all_resources)
- description and source-code
```javascript
delete_all_resources = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_derived_resources"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_derived_resources ()](#apidoc.element.cloudinary.v2.api.delete_derived_resources)
- description and source-code
```javascript
delete_derived_resources = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_resources"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_resources ()](#apidoc.element.cloudinary.v2.api.delete_resources)
- description and source-code
```javascript
delete_resources = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_resources_by_prefix"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_resources_by_prefix ()](#apidoc.element.cloudinary.v2.api.delete_resources_by_prefix)
- description and source-code
```javascript
delete_resources_by_prefix = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_resources_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_resources_by_tag ()](#apidoc.element.cloudinary.v2.api.delete_resources_by_tag)
- description and source-code
```javascript
delete_resources_by_tag = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_streaming_profile ()](#apidoc.element.cloudinary.v2.api.delete_streaming_profile)
- description and source-code
```javascript
delete_streaming_profile = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_transformation ()](#apidoc.element.cloudinary.v2.api.delete_transformation)
- description and source-code
```javascript
delete_transformation = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_upload_mapping ()](#apidoc.element.cloudinary.v2.api.delete_upload_mapping)
- description and source-code
```javascript
delete_upload_mapping = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.delete_upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>delete_upload_preset ()](#apidoc.element.cloudinary.v2.api.delete_upload_preset)
- description and source-code
```javascript
delete_upload_preset = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.get_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>get_streaming_profile ()](#apidoc.element.cloudinary.v2.api.get_streaming_profile)
- description and source-code
```javascript
get_streaming_profile = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.list_streaming_profiles"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>list_streaming_profiles ()](#apidoc.element.cloudinary.v2.api.list_streaming_profiles)
- description and source-code
```javascript
list_streaming_profiles = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.ping"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>ping ()](#apidoc.element.cloudinary.v2.api.ping)
- description and source-code
```javascript
ping = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.publish_by_ids"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>publish_by_ids ()](#apidoc.element.cloudinary.v2.api.publish_by_ids)
- description and source-code
```javascript
publish_by_ids = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.publish_by_prefix"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>publish_by_prefix ()](#apidoc.element.cloudinary.v2.api.publish_by_prefix)
- description and source-code
```javascript
publish_by_prefix = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.publish_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>publish_by_tag ()](#apidoc.element.cloudinary.v2.api.publish_by_tag)
- description and source-code
```javascript
publish_by_tag = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.resource"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resource ()](#apidoc.element.cloudinary.v2.api.resource)
- description and source-code
```javascript
resource = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.resource_types"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resource_types ()](#apidoc.element.cloudinary.v2.api.resource_types)
- description and source-code
```javascript
resource_types = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.resources"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources ()](#apidoc.element.cloudinary.v2.api.resources)
- description and source-code
```javascript
resources = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.resources_by_context"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_context ()](#apidoc.element.cloudinary.v2.api.resources_by_context)
- description and source-code
```javascript
resources_by_context = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.resources_by_ids"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_ids ()](#apidoc.element.cloudinary.v2.api.resources_by_ids)
- description and source-code
```javascript
resources_by_ids = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.resources_by_moderation"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_moderation ()](#apidoc.element.cloudinary.v2.api.resources_by_moderation)
- description and source-code
```javascript
resources_by_moderation = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.resources_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>resources_by_tag ()](#apidoc.element.cloudinary.v2.api.resources_by_tag)
- description and source-code
```javascript
resources_by_tag = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.restore"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>restore ()](#apidoc.element.cloudinary.v2.api.restore)
- description and source-code
```javascript
restore = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.root_folders"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>root_folders ()](#apidoc.element.cloudinary.v2.api.root_folders)
- description and source-code
```javascript
root_folders = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.sub_folders"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>sub_folders ()](#apidoc.element.cloudinary.v2.api.sub_folders)
- description and source-code
```javascript
sub_folders = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.tags"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>tags ()](#apidoc.element.cloudinary.v2.api.tags)
- description and source-code
```javascript
tags = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>transformation ()](#apidoc.element.cloudinary.v2.api.transformation)
- description and source-code
```javascript
transformation = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.transformations"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>transformations ()](#apidoc.element.cloudinary.v2.api.transformations)
- description and source-code
```javascript
transformations = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.update"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update ()](#apidoc.element.cloudinary.v2.api.update)
- description and source-code
```javascript
update = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
...
var config, crypto, digest;

crypto = require('crypto');

config = require('./config');

digest = function(message, key) {
  return crypto.createHmac("sha256", new Buffer(key, "hex")).update(message).digest('hex');
};

exports.generateAkamaiToken = function(options) {
  var auth, expiration, key, ref, ref1, ref2, start, tokenName, tokenParts;
  key = (ref = options.key) != null ? ref : config().akamai_key;
  tokenName = (ref1 = options.tokenName) != null ? ref1 : "__cld_token__";
  expiration = options.end_time;
...
```

#### <a name="apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_ids"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_resources_access_mode_by_ids ()](#apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_ids)
- description and source-code
```javascript
update_resources_access_mode_by_ids = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_prefix"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_resources_access_mode_by_prefix ()](#apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_prefix)
- description and source-code
```javascript
update_resources_access_mode_by_prefix = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_resources_access_mode_by_tag ()](#apidoc.element.cloudinary.v2.api.update_resources_access_mode_by_tag)
- description and source-code
```javascript
update_resources_access_mode_by_tag = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.update_streaming_profile"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_streaming_profile ()](#apidoc.element.cloudinary.v2.api.update_streaming_profile)
- description and source-code
```javascript
update_streaming_profile = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.update_transformation"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_transformation ()](#apidoc.element.cloudinary.v2.api.update_transformation)
- description and source-code
```javascript
update_transformation = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.update_upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_upload_mapping ()](#apidoc.element.cloudinary.v2.api.update_upload_mapping)
- description and source-code
```javascript
update_upload_mapping = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.update_upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>update_upload_preset ()](#apidoc.element.cloudinary.v2.api.update_upload_preset)
- description and source-code
```javascript
update_upload_preset = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.upload_mapping"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_mapping ()](#apidoc.element.cloudinary.v2.api.upload_mapping)
- description and source-code
```javascript
upload_mapping = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.upload_mappings"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_mappings ()](#apidoc.element.cloudinary.v2.api.upload_mappings)
- description and source-code
```javascript
upload_mappings = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.upload_preset"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_preset ()](#apidoc.element.cloudinary.v2.api.upload_preset)
- description and source-code
```javascript
upload_preset = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.upload_presets"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>upload_presets ()](#apidoc.element.cloudinary.v2.api.upload_presets)
- description and source-code
```javascript
upload_presets = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.api.usage"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.api.</span>usage ()](#apidoc.element.cloudinary.v2.api.usage)
- description and source-code
```javascript
usage = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cloudinary.v2.uploader"></a>[module cloudinary.v2.uploader](#apidoc.module.cloudinary.v2.uploader)

#### <a name="apidoc.element.cloudinary.v2.uploader.add_context"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>add_context ()](#apidoc.element.cloudinary.v2.uploader.add_context)
- description and source-code
```javascript
add_context = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.add_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>add_tag ()](#apidoc.element.cloudinary.v2.uploader.add_tag)
- description and source-code
```javascript
add_tag = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.create_archive"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>create_archive ()](#apidoc.element.cloudinary.v2.uploader.create_archive)
- description and source-code
```javascript
create_archive = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.create_zip"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>create_zip ()](#apidoc.element.cloudinary.v2.uploader.create_zip)
- description and source-code
```javascript
create_zip = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.destroy"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>destroy ()](#apidoc.element.cloudinary.v2.uploader.destroy)
- description and source-code
```javascript
destroy = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.direct_upload"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>direct_upload (callback_url, options)](#apidoc.element.cloudinary.v2.uploader.direct_upload)
- description and source-code
```javascript
direct_upload = function (callback_url, options) {
  var api_url, params;
  if (options == null) {
    options = {};
  }
  params = build_upload_params(_.extend({
    callback: callback_url
  }, options));
  params = utils.process_request_params(params, options);
  api_url = utils.api_url("upload", options);
  return {
    hidden_fields: params,
    form_attrs: {
      action: api_url,
      method: "POST",
      enctype: "multipart/form-data"
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.explicit"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>explicit ()](#apidoc.element.cloudinary.v2.uploader.explicit)
- description and source-code
```javascript
explicit = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.explode"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>explode ()](#apidoc.element.cloudinary.v2.uploader.explode)
- description and source-code
```javascript
explode = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.generate_sprite"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>generate_sprite ()](#apidoc.element.cloudinary.v2.uploader.generate_sprite)
- description and source-code
```javascript
generate_sprite = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.image_upload_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>image_upload_tag (field, options)](#apidoc.element.cloudinary.v2.uploader.image_upload_tag)
- description and source-code
```javascript
image_upload_tag = function (field, options) {
  var html_options, ref, tag_options;
  if (options == null) {
    options = {};
  }
  html_options = (ref = options.html) != null ? ref : {};
  tag_options = _.extend({
    type: "file",
    name: "file",
    "data-url": exports.upload_url(options),
    "data-form-data": exports.upload_tag_params(options),
    "data-cloudinary-field": field,
    "data-max-chunk-size": options.chunk_size,
    "class": [html_options["class"], "cloudinary-fileupload"].join(" ")
  }, html_options);
  return '<input ' + utils.html_attrs(tag_options) + '/>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.multi"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>multi ()](#apidoc.element.cloudinary.v2.uploader.multi)
- description and source-code
```javascript
multi = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.remove_all_context"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>remove_all_context ()](#apidoc.element.cloudinary.v2.uploader.remove_all_context)
- description and source-code
```javascript
remove_all_context = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.remove_all_tags"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>remove_all_tags ()](#apidoc.element.cloudinary.v2.uploader.remove_all_tags)
- description and source-code
```javascript
remove_all_tags = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.remove_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>remove_tag ()](#apidoc.element.cloudinary.v2.uploader.remove_tag)
- description and source-code
```javascript
remove_tag = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.rename"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>rename ()](#apidoc.element.cloudinary.v2.uploader.rename)
- description and source-code
```javascript
rename = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.replace_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>replace_tag ()](#apidoc.element.cloudinary.v2.uploader.replace_tag)
- description and source-code
```javascript
replace_tag = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.text"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>text ()](#apidoc.element.cloudinary.v2.uploader.text)
- description and source-code
```javascript
text = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.unsigned_image_upload_tag"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>unsigned_image_upload_tag (field, upload_preset, options)](#apidoc.element.cloudinary.v2.uploader.unsigned_image_upload_tag)
- description and source-code
```javascript
unsigned_image_upload_tag = function (field, upload_preset, options) {
  if (options == null) {
    options = {};
  }
  return exports.image_upload_tag(field, utils.merge(options, {
    unsigned: true,
    upload_preset: upload_preset
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.unsigned_upload"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>unsigned_upload ()](#apidoc.element.cloudinary.v2.uploader.unsigned_upload)
- description and source-code
```javascript
unsigned_upload = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.unsigned_upload_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>unsigned_upload_stream ()](#apidoc.element.cloudinary.v2.uploader.unsigned_upload_stream)
- description and source-code
```javascript
unsigned_upload_stream = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload ()](#apidoc.element.cloudinary.v2.uploader.upload)
- description and source-code
```javascript
upload = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
...

Assuming you have your Cloudinary configuration parameters defined ('cloud_name', 'api_key', 'api_secret'), uploading to Cloudinary
 is very simple.

The following example uploads a local JPG to the cloud:

	var cloudinary = require('cloudinary')

   cloudinary.uploader.upload("my_picture.jpg", function(result) { console.log(result) })

Below is an example of an upload's result:

	{ public_id: '4srvcynxrf5j87niqcx6w',
	  version: 1340625837,
	  signature: '01234567890abcdef01234567890abcdef012345',
	  width: 200,
...
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload_chunked"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_chunked ()](#apidoc.element.cloudinary.v2.uploader.upload_chunked)
- description and source-code
```javascript
upload_chunked = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload_chunked_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_chunked_stream ()](#apidoc.element.cloudinary.v2.uploader.upload_chunked_stream)
- description and source-code
```javascript
upload_chunked_stream = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload_large"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_large ()](#apidoc.element.cloudinary.v2.uploader.upload_large)
- description and source-code
```javascript
upload_large = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload_large_part"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_large_part ()](#apidoc.element.cloudinary.v2.uploader.upload_large_part)
- description and source-code
```javascript
upload_large_part = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload_stream"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_stream ()](#apidoc.element.cloudinary.v2.uploader.upload_stream)
- description and source-code
```javascript
upload_stream = function () {
  var args, callback, options, pass_args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  pass_args = _.take(args, num_pass_args);
  options = args[num_pass_args];
  callback = args[num_pass_args + 1];
  if ((callback == null) && _.isFunction(options)) {
    callback = options;
    options = {};
  }
  callback = v1_result_adapter(callback);
  args = pass_args.concat([callback, options]);
  return v1[name].apply(this, args);
}
```
- example usage
```shell
...
Setting the 'cloud_name', 'api_key' and 'api_secret' parameters can be done either directly in each call to a Cloudinary method,
by calling the cloudinary.config(), or by using the CLOUDINARY_URL environment variable.

### Overriding the request agent
To override the request agent pass the agent into any method that makes a
request and it will be used instead of the normal https agent. e.g
'''js

cloudinary.uploader.upload_stream(
  function(result) { console.log(result); },
  { agent: myAgent }
);

'''

### Embedding and transforming images
...
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload_tag_params"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_tag_params (options)](#apidoc.element.cloudinary.v2.uploader.upload_tag_params)
- description and source-code
```javascript
upload_tag_params = function (options) {
  var params;
  if (options == null) {
    options = {};
  }
  params = build_upload_params(options);
  params = utils.process_request_params(params, options);
  return JSON.stringify(params);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cloudinary.v2.uploader.upload_url"></a>[function <span class="apidocSignatureSpan">cloudinary.v2.uploader.</span>upload_url (options)](#apidoc.element.cloudinary.v2.uploader.upload_url)
- description and source-code
```javascript
upload_url = function (options) {
  if (options == null) {
    options = {};
  }
  if (options.resource_type == null) {
    options.resource_type = "auto";
  }
  return utils.api_url("upload", options);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
