# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a729c86d78552ec7e05e3748448e7a99f6f2a696',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'f47ac1956e0206f8f908e2ac6f982a4058001d72',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ec59c77a3bb5c747a369931ef101ac7c14823f2f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '4554c6b7ea7625637c3b6a2c82fe75c0ac6c2104',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '29f979ee5aa58b7b005f805ea8df7a855c39ff37',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8bdce6d842ca9f9bd0a4119963b0eb10693f5b23',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6991ccb68890681b1a3e0f56acd8f53b20ad1e79',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '0a786ee3e4fd3602f68ff0ffd9fdcb12e0efb646',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ba3c0374294673acf653cc536e2c0278cc0a41af',
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
