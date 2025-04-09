# ffmpeg-6.1_debian12

**FFmpeg 6.1 built from source with extended codec support for Debian 12**

FFmpeg is a powerful multimedia framework that can decode, encode, transcode, mux, demux, stream, filter, and play almost anything that humans and machines have created.

This custom build provides FFmpeg version **6.1**, compiled from source on **Debian 12**, with extended codec and hardware support. Ideal for advanced media processing workflows and broadcasting tools like **ErsatzTV**.

---

## Features

- Built from source with full codec support
- Includes support for:
  - `libx264`, `libx265`, `libvpx`, `libopus`, `libaom`, `libsvtav1`, `libfdk-aac`, etc.
- Compatible with hardware acceleration (VAAPI, NVENC, etc.)
- For Debian 12 environments

---

## Installation

### 1. Install dependencies

```bash
sudo apt update
sudo sudo apt install alsa-topology-conf alsa-ucm-conf fontconfig fontconfig-config fonts-dejavu-core i965-va-driver intel-media-va-driver libaacs0 libaom3 libasound2 libasound2-data libass9 libasyncns0 libavc1394-0 libavcodec59 libavdevice59 libavfilter8 libavformat59 libavutil57 libbdplus0 libblas3 libbluray2 libbs2b0 libcaca0 libcairo-gobject2 libcairo2 libcdio-cdda2 libcdio-paranoia2 libcdio19 libchromaprint1 libcjson1 libcodec2-1.0 libdatrie1 libdav1d6 libdc1394-25 libdecor-0-0 libdecor-0-plugin-1-cairo libdeflate0 libdrm-amdgpu1 libdrm-common libdrm-intel1 libdrm-nouveau2 libdrm-radeon1 libdrm2 libepoxy0 libflac12 libflite1 libfontconfig1 libfribidi0 libgbm1 libgdk-pixbuf-2.0-0 libgdk-pixbuf2.0-bin libgdk-pixbuf2.0-common libgfortran5 libgl1 libgl1-mesa-dri libglapi-mesa libglib2.0-0 libglib2.0-data libglvnd0 libglx-mesa0 libglx0 libgme0 libgomp1 libgraphite2-3 libgsm1 libharfbuzz0b libhwy1 libiec61883-0 libigdgmm12 libjack-jackd2-0 libjbig0 libjpeg62-turbo libjxl0.7 liblapack3 liblcms2-2 liblerc4 liblilv-0-0 libllvm15 libmbedcrypto7 libmfx1 libmp3lame0 libmpg123-0 libmysofa1 libnorm1 libnuma1 libogg0 libopenal-data libopenal1 libopenjp2-7 libopenmpt0 libopus0 libpango-1.0-0 libpangocairo-1.0-0 libpangoft2-1.0-0 libpciaccess0 libpgm-5.3-0 libpixman-1-0 libplacebo208 libpocketsphinx3 libpostproc56 libpulse0 libquadmath0 librabbitmq4 librav1e0 libraw1394-11 librist4 librsvg2-2 librsvg2-common librubberband2 libsamplerate0 libsdl2-2.0-0 libsensors-config libsensors5 libserd-0-0 libshine3 libsnappy1v5 libsndfile1 libsndio7.0 libsodium23 libsord-0-0 libsoxr0 libspeex1 libsphinxbase3 libsratom-0-0 libsrt1.5-gnutls libssh-4 libssh-gcrypt-4 libsvtav1enc1 libswresample4 libswscale6 libthai-data libthai0 libtheora0 libtiff6 libtwolame0 libudfread0 libva-drm2 libva-x11-2 libva2 libvdpau-va-gl1 libvdpau1 libvidstab1.1 libvorbis0a libvorbisenc2 libvorbisfile3 libvpl2 libvpx7 libvulkan1 libwayland-client0 libwayland-cursor0 libwayland-egl1 libwayland-server0 libwebp7 libwebpmux3 libx11-xcb1 libx264-164 libx265-199 libxcb-dri2-0 libxcb-dri3-0 libxcb-glx0 libxcb-present0 libxcb-randr0 libxcb-render0 libxcb-shape0 libxcb-shm0 libxcb-sync1 libxcb-xfixes0 libxcursor1 libxfixes3 libxi6 libxkbcommon0 libxrandr2 libxrender1 libxshmfence1 libxss1 libxv1 libxvidcore4 libxxf86vm1 libz3-4 libzimg2 libzmq5 libzvbi-common libzvbi0 mesa-va-drivers mesa-vdpau-drivers mesa-vulkan-drivers ocl-icd-libopencl1 pocketsphinx-en-us shared-mime-info va-driver-all vdpau-driver-all x11-common xdg-user-dirs
```

### 2. Clone the repository and install the package
```bash
wget https://github.com/keystone-sideral/ffmpeg-6.1_debian12/releases/download/ffmpeg_6.1/ffmpeg_6.1-0+deb12u1_amd64.deb
sudo dpkg -i ffmpeg_6.1-0+deb12u1_amd64.deb
```

### 3. Verify installation
```bash
ffmpeg -version
```

