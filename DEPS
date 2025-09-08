# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9d764997360b202d2ba7aaad9a401e57d8df56b3',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '055b25c02fa80cdcca77fcf94ab64a02f02d9199',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '54ae32bce772b29a253b18583b86ab813ed1887c',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bd997c5506f480d742f9c843a5133898410e55ae',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd1cd37e925510a167d4abef39340dbdea47d8989',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3af548220a6a256fdb7e03443ce92d26b2fc3b84',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c9ed944bb39a564dbf15d0bdda63cc145018ed84',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a0543a68cca0de632c010724fad08fce0bc27679',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0413ed43f161a014f46b81cd90689e7d097b487a',
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
