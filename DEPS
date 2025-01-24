# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'bd1f1c263fc10969eb4a4b393e774a75ffcb2673',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '3f129d076b44221b8b56a63215446d33b570ced8',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '2b2e05e088841c63c0b6fd4c9fb380d8688738d3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e02275ec02b68e3d175528f768871c97ae9eee90',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e43027aa41c4f51b12d79aeae53ff608951c36ec',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1586f33d6d79eb9ffa5963ce4f70423986b95d8a',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8ce2501d2511b6f4e6389a03ff08c4e84d54fa25',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'f07e27717a642fa193c967440f21ed634ea17987',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'afad70fbb26c643b19cf53a5990852a4d83664b6',
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
