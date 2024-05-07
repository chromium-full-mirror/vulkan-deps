# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e8dd0b6903b34f1879520b444634c75ea2deedf5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '5e3ad389ee56fca27c9705d093ae5387ce404df4',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9241a58a8028c49510bc174b6c970e3c2b4b8e51',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4bc77c26ff9ce89cf4a4f79e1c24a44604132d53',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e69a59a96b241038f24a0e425445d001ea099b2c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8b6228a69820bd315761323c763b6272bdc8c720',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ad7f699a7b2b5deb66eb3de19f24aa33597ed65b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd9cdffbdbaef9ad73a7143371e8def06ecbbfa3a',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
