# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c1734f62051d37dbe5d62c0101cd72becfc631ad',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'be9744eb74f522c6829c5e8d842cc29dce8259bd',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c63848ecf2200425511319fd8bf2c17b751e501e',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '58fe144fdc8847b303be51d4f8fcc9e7da17056e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '01393c3df0e5285b54ee6527466513f9e614be94',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ddaf5c7c2302b07ef2385727c9a54b073ebb563e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'b7ae55b37cda76d16368c302f37cb0c7ea2f8409',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '8183a0b86632bf1107553eab1e69d7b85d455477',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a507c30330c2fe18ffc4d8179a3fb775cf79ffc1',
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
