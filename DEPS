# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1e38440e102772fb99d9395ae161c5c9b3c88f11',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '98254945250cdf47d66779d427bed964071d7271',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'fef168c54ed2e37c314eb251806aaf9877f38465',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '28f99f74a2a922ff85fc8fd966d6b3d6a45be795',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '73814d006638aa00bd553215b054f0f02e457e22',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'dfe4acf7aae309eb52453afce2ed2e4f886a72d5',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c38e7c390892e06fe4c84f0c19fb891c79f885d9',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'da050a01c5518cc270f2ff1dd736bf5631d942db',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0dfd4884ba0ff2837b69d85f68ed4c3e8adcc96d',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
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
