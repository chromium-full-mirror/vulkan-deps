# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'dbe01f4dcb282e1a38138813e389dff6548fbb6f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e1f872619095e51d3f310be320e77347de1158d4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'aaffbc59b41bf8faea671b0d1c6b34a584c45171',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '2acb87f86d6906847d5f4c0c805c54604abb1b01',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '015e25c3c91b70eb1a754d36fb14c4ba6ad9b0b9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e99951e806943624c12e1609aff8b0a22f0cc558',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e3d18f90c0b8ef1f52539e0674a42f0adfe30381',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '28d3b5930a6da0e4f15040679d8b51dda0b29c86',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4ed4ca428c3a2da3b7951d5a60988a7d44ac5ad0',
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
