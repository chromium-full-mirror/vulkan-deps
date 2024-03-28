# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8c0199c4fd186b2e4d736335d0e26fec34e30726',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4f7b471f1a66b6d06462cd4ba57628cc0cd087d7',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'fe7bae090629f64115eb41aa8c41df419cef9159',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'cfebfc96b2b0bce93da7d12f2c14cc01793ae25c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'f60412f5a62ab9c817355999d0858893db7d404b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '3617af28811d9cc15fc2bb5b4a6565cd19b08089',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'd90f5c7eb1dcfe6ee21363d3c73200425eb6e8b8',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '071c9ef3b74b9750be5f1b79c14483d9dd545163',
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
