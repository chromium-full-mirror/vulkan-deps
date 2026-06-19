# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '20960a4872f681e4213312b06b48cc4ddae3c73d',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '11e4ae3b615e81648a984790006350876225c3d2',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c63848ecf2200425511319fd8bf2c17b751e501e',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b9250830dd7aa056bb94464cd978a40564028cf2',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '01393c3df0e5285b54ee6527466513f9e614be94',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'b52703d439c3077705db64e61c186545ddfdb2c7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'db008c1ac735713164b498f36b796bc7f00387f3',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '8183a0b86632bf1107553eab1e69d7b85d455477',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '21278efc46897c35bff6bdf13524c5ccb2990ffc',
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
