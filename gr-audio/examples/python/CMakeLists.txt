# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.

include(GrPython)

GR_PYTHON_INSTALL(PROGRAMS
    audio_copy.py
    audio_fft.py
    audio_play.py
    audio_to_file.py
    dial_tone.py
    dial_tone_daemon.py
    dial_tone_wav.py
    mono_tone.py
    multi_tone.py
    noise.py
    spectrum_inversion.py
    test_resampler.py
    DESTINATION ${GR_PKG_AUDIO_EXAMPLES_DIR}
    COMPONENT "audio_python"
)
