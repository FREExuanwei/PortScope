# Third-party source availability / 第三方源码说明

These materials apply to third-party components only, not to PortScope's own license. No project license has been selected.

MPL-covered dependency sources: supplemental/sources contains the exact unmodified Cargo .crate archives used by the locked Windows build. SHA256 values match Cargo.lock; provenance.json records versions and official source URLs. MPL text and the original file-level notices accompany these sources. This does not relicense PortScope.

Missing package-root notices were retrieved from the exact packaged upstream VCS revisions; provenance.json records their origin and hashes. Both MIT/Apache notices are supplied where upstream offers alternatives; no PortScope license is inferred.

The statically linked Microsoft WebView2 loader matches SDK1.0.3800.47 from official NuGet byte-for-byte. Its SDK LICENSE.txt is supplied in supplemental/microsoft-webview2-sdk. The WebView2 browser runtime itself is not bundled or installed by PortScope.

NSIS3.11: NSIS-COPYING.txt contains the original notices, including the LZMA special linking exception. Unmodified upstream source is available at https://sourceforge.net/projects/nsis/files/NSIS%203/3.11/ . The linking exception does not remove obligations applicable to the NSIS components themselves or modified component sources.

Official guidance: https://www.mozilla.org/en-US/MPL/2.0/FAQ/ and https://nsis.sourceforge.io/Docs/AppendixI.html . Source and notice review does not authorize public publication or replace the owner's licensing/business decisions.
