# Changelog

## v0.3.1
**BassMix**
* Added ChannelAttribute.MixerLatency.
* Updated BassMix.ChannelSetMatrix(int, float[,], float) documentation.

**BassEnc v2.4.13**
* Added EncodeServer.Meta.
* Added EncodeFlags.Dither, ConvertFloatAuto.
* Improved BassEnc.CastProxy.

**BassHls**
* Added SyncFlags.HlsSegment.
* Added TagType.HlsExtInf.
* Added FileStreamPosition.HlsSegment.

## v0.3.0
Completed XML Documentation!

* Added `BassMidi.StreamGetMark` overload returning `MidiMarker`.
* Modified the signature of `BassMidi.StreamGetMarks` overload returning `MidiMarker[]`.
* Added `Errors.CastDenied`, `AcmCancel`.
* Added `BassMidi.StreamEvents` `byte[]` overload with Channels parameter.
* Added `BassMidi.StreamGetFonts` overload returning `MidiFont[]`.
* Added `BassMidi.StreamGetFontsEx`.

## v0.2.1
Fixed the iOS Library!

* More Xml Documentation.
* `EncodeProcedureEx` is available only on iOS and Mac.
* Added `BassMidi.StreamEvent` overload taking High and Low parameters.
* Removed Obsolete members.
* FIX: `EncodeClientProcedure` - Changed Headers parameter to `IntPtr`.
* FIX: `WasapiInfo` - Changed MaxVolume, MinVolume and VolumeStep properties to `float`.

## v0.1.1
* More XML Documentation.
* Marked `BassEnc.CastSendMeta` obsolete and added other overloads.
* Marked `BassMidi.FontInit` obsolete and added overload without `BassFlags`.

## v0.1.0
Initial Release.